# Histórico de versões

## StageFlow para Mac e Windows

### 2.25.3
- **Procurar atualizações:** lê o ficheiro de versões nas duas cópias do GitHub (API e "raw") e fica com a versão mais recente, para encontrar a versão nova logo depois de publicada mesmo que uma das cópias ainda esteja em cache.

### 2.25.2
- **Procurar atualizações:** a versão nova é encontrada logo depois de publicada. A StageFlow lê o ficheiro de versões pela API do GitHub (a cópia anterior passava por uma cache que podia servir o ficheiro antigo durante algum tempo) e o botão volta sempre a perguntar ao GitHub.

### 2.25.1
- Os botões 1080p / 720p e Low / Medium ficam com a mesma altura dos interruptores NDI e OMT; o interruptor ligado volta a verde vivo.

### 2.25
- **Saídas:** o NDI e o OMT têm cada um a sua resolução (botões 1080p / 720p ao lado de cada interruptor). A saída é desenhada na maior resolução pedida e reduzida para a outra; mudar um protocolo não interrompe o outro.

### 2.24
- **Relógio com mais de 3 palcos:** no máximo 3 palcos por linha; os seguintes passam para a linha de baixo, com a mesma largura.
- **Esc numa saída em ecrã inteiro:** sai do ecrã inteiro e a saída continua numa janela no mesmo monitor.

### 2.23
- **Saídas OMT (Open Media Transport)** ao lado do NDI, com qualidade **Low** ou **Medium**. Não é preciso instalar nada: a biblioteca oficial do OMT (licença MIT) vai dentro da StageFlow. Mac: macOS 15 ou mais recente; Windows: x64.
- As fontes OMT são encontradas pelo vMix, pelo OBS (plugin OMT) e por outros recetores; o nome é encurtado quando o nome do computador é comprido.
- OSC: `/stageflow/a/omt/tecnico` (também `/backstage`, `/detalhado`) e `/stageflow/a/omt/tecnico/qualidade "low"|"medium"`.

### 2.22.0
- **Desfazer e refazer** na consola: `Cmd+Z` / `Shift+Cmd+Z` no Mac, `Ctrl+Z` / `Ctrl+Y` no Windows, e no menu **Editar**. Desfaz alterações na Programação e no Projeto, com um aviso do que foi desfeito.
- Os comandos de direto (atraso, modo, Seguinte, Pausa, mensagens, mira, dia em direto) não se desfazem.
- Dentro de um campo de texto, o atalho desfaz só a escrita. Se outro aparelho alterou o projeto entretanto, pede confirmação.

### 2.21.1
- A **interface clássica foi retirada**: a consola abre sempre na interface nova, em todos os aparelhos.

### 2.21
- A **interface nova** passa a ser a oficial e abre por defeito em todos os aparelhos. Servidor, ecrãs, OSC, licenças e formato dos projetos não mudam.

### 2.20.3
- **Relógio com 3 ou mais palcos:** relógio mais pequeno e cartões mais compactos; os cartões dos palcos ficam alinhados ao topo.

### 2.20.2
- **Backstage:** a hora de fim aparece só no evento em curso ("Termina às HH:MM"). No modo manual mostra a hora prevista de fim em vez da duração.

### 2.20.1
- **Grupos na Programação:** as linhas de um grupo ficam com a cor do grupo em fundo suave.

### 2.20
- **Ocultar linha:** o ícone do olho oculta uma linha nos ecrãs, sem a tirar da programação nem dos tempos.
- **Marcos:** linhas sem horário nem categoria (ex.: mudar águas do palco), onde só se editam o evento e as notas. Não aparecem nos ecrãs por defeito; no editor de layouts, o elemento Lista tem a opção "Mostrar marcos".
- **Cor dos grupos**, escolhida no cabeçalho do grupo.
- **Mensagem para um ecrã:** em **Rede e OSC**, cada equipamento online tem um ícone para enviar uma mensagem em ecrã inteiro durante 10 segundos, com cor à escolha, quem envia e o IP.

### 2.19.1
- As linhas sem horário aparecem no Relógio da consola e nas listas dos ecrãs, com "--:--", barra branca e fundo cinzento.

### 2.19
- **Relógio** (antigo "Direto"): evento em curso e seguinte maiores, letra do palco antes do nome.
- **Programação:** edição direta na linha, menu do tipo de evento na barra de cor, arrastar linhas (os horários voltam a encadear), **grupos** com nome e tempo total, linhas sem horário, pinta verde no dia em direto.
- **Rede e OSC:** zona **Equipamentos online**, com a saída de cada ecrã, identificar e pré-visualização ao vivo do que está a sair.
- **Identificar** mostra também o palco.

### 2.18
- Interface nova (beta): saídas numa linha cada, Projeto em listas limpas, Rede e OSC e Licença sem caixas.

### 2.17
- Interface nova (beta): **Programação** com seleção múltipla, soma de tempos e **Mover −5 / +5**; categoria por barra de cor com menu; Projeto com arrastar para ordenar.

### 2.16
- **Interface nova (beta)**, opcional: menu de topo por áreas (Direto, Programação, Saídas, Projeto, Rede e OSC, Licença), contagem maior e comandos com símbolos.

### 2.15.1
- **TVs Samsung:** corrigida a rotação do ecrã na StageFlow TV para Samsung.

### 2.15.0
- **Identificar um ecrã:** em **Ecrãs ligados**, o ícone de identificar faz o aparelho mostrar durante 10 segundos um ecrã amarelo com o nome e o IP. Pela rede exige PIN.
- Numa TV com **Rodar ecrã** definido, os layouts com rotação "Automática" deixam de rodar a imagem.

### 2.14.0
- **Procurar atualizações:** verificação ao abrir, de 6 em 6 horas e no menu **Procurar atualizações…**. Aviso na consola e no cartão Licença, com **Descarregar** e **Novidades**. A instalação continua manual: nada se instala a meio de um espetáculo.

### 2.13.1
- O cartão **Licença** mostra o produto e a versão instalada.
- As licenças da Server TV usam o mesmo sistema da StageFlow.

### 2.13
- **Miniaturas ao vivo** de cada saída na consola, com os botões **Ver** e **Layout**.
- **Ecrãs ligados:** lista das TVs e navegadores que estão a mostrar uma saída, com nome editável, IP e saída atual. A saída de cada ecrã muda-se à distância, na consola ou no controlo móvel.
- **PIN obrigatório** para mudar ecrãs, aplicar e guardar layouts e criar ou apagar saídas. Sem PIN, os outros aparelhos ficam só em modo de visualização.
- Controlo móvel: a caixa da mensagem já não sai do ecrã em telemóveis estreitos.

### 2.12
- **StageFlow para Windows** (versão de teste), com as mesmas funções da versão Mac.
- Textos adaptados ao sistema ("computador" em vez de "Mac", Ctrl em vez de Cmd).

### 2.11.2
- Sem licença, de 5 em 5 minutos todas as saídas ficam vermelhas durante 10 segundos com "VERSÃO DEMONSTRAÇÃO".

### 2.11.1
- Barra de cor do tipo de evento mais larga na Programação.
- Cores nas etiquetas das notas técnicas (por omissão: Áudio azul, Luz amarelo, Vídeo verde).

### 2.11
- **Licenças offline**, assinadas pela Eventuais. Sem licença, a app funciona em modo demonstração.

### 2.10
- Nova app **StageFlow TV** para Android TV e Google TV, servida pela própria StageFlow em `/tv.apk`.

### 2.9
- **Notas técnicas por departamento** (Áudio, Luz, Vídeo e etiquetas próprias), nos layouts, no Excel/CSV e no OSC.

### 2.8
- **Captura de ecrã** e **entradas NDI** nos layouts. Layout predefinido "Captura + relógio".

## StageFlow Server TV

### 1.3.0
- **Rodar ecrã** no menu: 0°, 90°, 180° ou 270°, para TVs montadas na vertical.
- **Identificar** nos Ecrãs ligados: ecrã amarelo com o nome e o IP.
- O item **Atualizações** passa a chamar-se **Procurar atualizações**.

### 1.2.0
- Nova opção **Atualizações** no menu da TV: descarrega a versão nova e abre o instalador do Android. Na primeira vez é preciso autorizar a app a instalar apps desconhecidas.

### 1.1.1
- Envia a versão instalada para o cartão Licença da consola.

### 1.1.0
- Aparece em **Ecrãs ligados**: a consola e o controlo móvel podem mudar a saída mostrada na TV, mesmo com o menu aberto.

### 1.0.0
- Primeira versão: servidor StageFlow numa TV Android, consola no navegador, controlo móvel com PIN, OSC, arranque com a TV e saída em ecrã inteiro.

## StageFlow TV

### 1.2.0
- **Rodar ecrã** em Opções: 0°, 90°, 180° ou 270°, para TVs montadas na vertical.

### 1.1.0
- **Procurar atualizações** em Opções; quando há versão nova, **Atualizar** descarrega-a e abre o instalador do Android.

### 1.0.5
- Com uma saída no ecrã, **Voltar** abre a lista de saídas do mesmo servidor.

### 1.0.4
- Corrigido o regresso imediato ao menu ao escolher uma saída com o comando.

### 1.0
- Primeira versão: procura servidores na rede, mostra uma saída em ecrã inteiro e memoriza a última saída.

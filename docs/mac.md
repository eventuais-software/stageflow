# StageFlow para Mac

Servidor e consola principal da StageFlow, para Macs com Apple Silicon (M1 ou mais recente).

## O que faz

- **Consola de operador:** programação por dia e por palco, modo automático ou manual, atrasos, mensagens para os ecrãs e projetos.
- **Servidor da rede local:** os outros aparelhos abrem `http://IP-do-Mac:8080/` no navegador.
- **Saídas:** Técnico, Backstage, Detalhado e saídas personalizadas, com editor de layout. Cada saída pode abrir numa janela, em ecrã inteiro noutro monitor (Esc volta a janela) ou como **fonte NDI** e/ou **OMT**, cada uma em 1080p ou 720p; o OMT em qualidade Low ou Medium.
- **Consola por áreas:** Relógio, Programação, Saídas, Projeto, Rede e OSC, Licença. A Programação edita-se diretamente na linha, com grupos, marcos (linhas sem horário), linhas ocultas e arrastar para reordenar.
- **Equipamentos online** (Rede e OSC): lista das TVs e navegadores que estão a mostrar uma saída, com pré-visualização ao vivo. A saída de cada um muda-se à distância, e é possível identificar o ecrã ou enviar-lhe uma mensagem em ecrã inteiro, com PIN.
- **Controlo móvel** no telemóvel, com PIN.
- **OSC** para mesas de luz, som e vídeo (porta 9000).
- **Entradas de vídeo nos layouts:** fontes NDI, OMT, câmaras ou placas de captura e captura de ecrã.

## Instalar

1. Descarregue `StageFlow-Mac-<versão>.zip` em [Releases](https://github.com/eventuais-software/stageflow/releases) e descompacte-o.
2. Arraste **StageFlow.app** para a pasta **Aplicações**.
3. **Primeira abertura:** como a app não é distribuída pela App Store, o macOS pode bloqueá-la. Abra **Definições do Sistema › Privacidade e Segurança** e carregue em **Abrir mesmo assim**.
4. Quando o macOS perguntar se a StageFlow pode receber ligações da rede, escolha **Permitir**.

**Procurar atualizações:** a StageFlow verifica sozinha ao abrir e mostra um aviso na consola quando há versão nova. Também se verifica no menu **Procurar atualizações…**.

**Atualizar:** feche a StageFlow e substitua a app na pasta Aplicações. A programação, os layouts, a licença e as definições ficam guardados e mantêm-se.

## Requisitos

- Mac com Apple Silicon (M1 ou mais recente), com uma versão recente do macOS.
- Para NDI: as **NDI Tools** ou o **NDI Runtime** (ndi.video).
- Para OMT: nada a instalar (vai dentro da StageFlow); exige macOS 15 ou mais recente.
- Para captura de ecrã nos layouts: autorizar a StageFlow em **Privacidade e Segurança › Gravação de ecrã**.

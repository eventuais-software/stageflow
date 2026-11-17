# StageFlow para Windows (versão de teste)

As mesmas funções da StageFlow para Mac, em Windows 10 e 11 de 64 bits.

## Instalar

1. Descarregue `StageFlow-Windows-<versão>.zip` em [Releases](https://github.com/eventuais-software/stageflow/releases).
2. Descompacte-o, por exemplo para `C:\StageFlow`, e abra `StageFlow.exe`. Não é preciso instalar.
3. **Primeira vez:** como a app ainda não tem assinatura digital, o Windows pode mostrar "O Windows protegeu o computador". Carregue em **Mais informações** e depois em **Executar mesmo assim**.
4. **Firewall:** quando o Windows perguntar se a StageFlow pode usar a rede, escolha **Permitir** (redes privadas). Sem isto, os ecrãs de rede, a StageFlow TV e o OSC não conseguem ligar.

**Procurar atualizações:** a StageFlow verifica sozinha ao abrir e mostra um aviso na consola quando há versão nova. Também se verifica no menu **Procurar atualizações…**.

**Atualizar:** feche a StageFlow (ícone junto ao relógio › **Sair da StageFlow**) e substitua a pasta pela da versão nova. Os dados ficam em `%APPDATA%\StageFlow\dados` e mantêm-se.

## Notas

- **NDI:** instale o **NDI Runtime** ou as **NDI Tools** (ndi.video).
- **OMT:** não é preciso instalar nada. Permita a StageFlow na firewall (redes privadas) para os recetores a encontrarem.
- **Fechar a consola não fecha a StageFlow:** os ecrãs, o NDI e o OSC continuam ativos. A app fica no ícone junto ao relógio (pode estar escondido na seta ^).
- O **ID deste computador**, para a licença, aparece no cartão **Licença** da consola.

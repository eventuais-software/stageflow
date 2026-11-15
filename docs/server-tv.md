# StageFlow Server TV (Android TV / Google TV)

A StageFlow a correr **dentro de uma TV Android**: a própria TV é o servidor, sem computador. Os outros aparelhos ligam-se a ela pela rede, como a um Mac com a StageFlow.

## O que faz

- **Servidor permanente:** continua ligado mesmo com a TV noutra app (aparece a notificação "StageFlow Server TV").
- **Consola no navegador:** programação, editor de layout, projetos, definições e licença, no endereço mostrado na TV (por exemplo `http://192.168.1.50:8080`).
- **Ecrãs ligados:** na consola e no controlo móvel vê-se que TVs e navegadores estão ligados e muda-se a saída de cada um, incluindo a da própria Server TV. Exige PIN.
- **Controlo móvel com PIN:** código QR no menu da TV.
- **OSC** na porta 9000.
- **Outras TVs:** com a app StageFlow TV, que encontra este servidor sozinha.
- **Ecrã da própria TV:** mostra uma saída em ecrã inteiro.
- **Arrancar com a TV** e **abrir logo em ecrã inteiro** (opções no menu).

**Não tem:** saídas e entradas NDI, captura de ecrã, nem janelas noutros monitores.

## Instalar (TV sem USB)

1. Na TV, instale a app gratuita **Downloader** (AFTVnews) a partir da Play Store.
2. Ative as opções de programador: **Definições › Sistema › Acerca › Compilação do SO**, carregue várias vezes em OK.
3. Em **Definições › Apps › Segurança e restrições › Fontes desconhecidas**, autorize o **Downloader**.
4. No Downloader, escreva o link da versão (está em [Releases](https://github.com/eventuais-software/stageflow/releases)) e escolha **Instalar**.

**Atualizar:** instale a versão nova por cima. A programação, o PIN e a licença mantêm-se.

## Menu no comando

| Opção | O que faz |
|---|---|
| Mostrar no ecrã | Mostra a saída escolhida em ecrã inteiro. OK ou Voltar regressam ao menu. |
| Palco / Saída | OK passa ao seguinte. |
| Arrancar com a TV | Ao ligar a TV, arranca o servidor e abre a StageFlow. |
| Abrir logo em ecrã inteiro | Ao abrir, mostra logo a saída escolhida. |
| PIN | Define o PIN do controlo móvel, com o teclado numérico do ecrã ou do comando. |
| Licença | Mostra o ID da TV e o estado da licença. |

## Requisitos

Android 7 ou mais recente, 32 ou 64 bits. Recomendado: 2 GB de RAM ou mais e ligação por cabo de rede.

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
- **Rodar ecrã** (a partir da 1.3.0): 0°, 90°, 180° ou 270°, para TVs montadas na vertical.
- **Arrancar com a TV** e **abrir logo em ecrã inteiro** (opções no menu).

**Não tem:** saídas e entradas NDI, captura de ecrã, nem janelas noutros monitores.

## Instalar (TV sem USB)

1. Na TV, instale a app gratuita **Downloader** (AFTVnews) a partir da Play Store.
2. Ative as opções de programador: **Definições › Sistema › Acerca › Compilação do SO**, carregue várias vezes em OK.
3. Em **Definições › Apps › Segurança e restrições › Fontes desconhecidas**, autorize o **Downloader**.
4. No Downloader, escreva o link da versão (está em [Releases](https://github.com/eventuais-software/stageflow/releases)) e escolha **Instalar**.

**Atualizar:** a partir da versão 1.2.0, no menu da TV, em **Procurar atualizações** (na primeira vez o Android pede para autorizar a app a instalar apps desconhecidas). Também pode instalar a versão nova por cima pelo Downloader. A programação, o PIN e a licença mantêm-se. Atualize fora de um espetáculo.

## Menu no comando

| Opção | O que faz |
|---|---|
| Mostrar no ecrã | Mostra a saída escolhida em ecrã inteiro. OK ou Voltar regressam ao menu. |
| Palco / Saída | OK passa ao seguinte. |
| Rodar ecrã | OK passa ao ângulo seguinte (0°, 90°, 180°, 270°). O menu e a saída rodam juntos. Numa TV vertical use o Backstage ou uma saída vertical. |
| Arrancar com a TV | Ao ligar a TV, arranca o servidor e abre a StageFlow. |
| Abrir logo em ecrã inteiro | Ao abrir, mostra logo a saída escolhida. |
| PIN | Define o PIN do controlo móvel, com o teclado numérico do ecrã ou do comando. |
| Licença | Mostra o ID da TV e o estado da licença. |
| Procurar atualizações | Mostra a versão instalada; se houver uma nova, **Atualizar** descarrega-a e o Android pede confirmação. |

## Requisitos

Android 7 ou mais recente, 32 ou 64 bits. Recomendado: 2 GB de RAM ou mais e ligação por cabo de rede.

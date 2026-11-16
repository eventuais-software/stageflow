# StageFlow TV (Android TV / Google TV)

Mostra uma saída da StageFlow (Técnico, Backstage, Detalhado ou personalizada) em ecrã inteiro numa TV Android, Google TV, ou em qualquer TV com uma box Android por HDMI (Google TV Streamer, Chromecast com Google TV, Fire TV Stick).

## Instalar

**Pela rede, sem pen USB**
1. Na TV, instale a app gratuita **Downloader**.
2. Escreva o endereço do servidor StageFlow seguido de `tv.apk` (por exemplo `http://192.168.1.103:8080/tv.apk`), ou o link da versão em [Releases](https://github.com/eventuais-software/stageflow/releases).
3. Aceite a instalação. Da primeira vez, o Android pede para autorizar o Downloader a instalar apps desconhecidas.

**Por pen USB**
Copie o APK para uma pen, ligue-a à TV e abra-o num gestor de ficheiros.

## Usar

- Ao abrir, a app procura servidores StageFlow na rede. Se não encontrar, escreva o endereço.
- Escolha o servidor, o palco e a saída. A saída fica em ecrã inteiro e a TV não adormece.
- **OK** ou **Voltar** abrem a lista de saídas do mesmo servidor. Um segundo Voltar leva ao ecrã inicial.
- A saída também pode ser mudada **à distância**, a partir da consola ou do controlo móvel (Ecrãs ligados).
- A app memoriza a última saída e abre-a ao iniciar. Opção para arrancar quando a TV liga.
- Se a ligação falhar, tenta de novo sozinha e volta à saída.
- **Rodar ecrã** (versão 1.2.0 ou mais recente): em Opções, cada OK passa ao ângulo seguinte (0°, 90°, 180°, 270°), para TVs montadas na vertical. A escolha fica memorizada.
- **Atualizações** (versão 1.1.0 ou mais recente): em Opções, **Procurar atualizações**. Quando há versão nova, **Atualizar** descarrega-a e o Android pede confirmação.

## Requisitos

Android 5.0 ou mais recente, com o "Android System WebView" atualizado. A TV e o servidor têm de estar na mesma rede.

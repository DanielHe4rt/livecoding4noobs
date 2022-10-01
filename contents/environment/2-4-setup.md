# Configurando seu ambiente

Na melhor das hipóteses, você pode ser o tipo de streamer que faz live só com uma `cena` que é compartilhando sua tela. Mas e se a gente fazer um padrão de telas que vão ser o `básico` pra todo streamer, sendo elas:

- Inicio
- Foco
- Conversando
- Finalizando

## Tela de Inicio

Pensa que você tá esperando um programa de TV começa e tem uma intro/vinheta que introduz o apresentador. Pensou? Então, é a mesma coisa. O seu 'programa' já está pra começar e precisam ter informações pertinentes à o que você vai fazer.

Informações Necessárias:

- Titulo
  1. Iniciando Live
  2. Já vai começar
  3. Tópico: como fazer maconha com javascript e maizena
  4. etc

# Configurações do OBS

O OBS tem várias sessões quando é clicado em configurações, vamos citar as mais importantes para você começar sua live com qualidade.

### Codificador

Normalmente o OBS te oferece 2 opções para ser o seu codificador durante as lives, a sua placa de vídeo ou o seu processador, recomendamos que você coloque sua placa de vídeo (NVIDEA NVENC), mas vai de cada caso pra qual se encaixa melhor para seu setup.

![Codificador](/assets/Codificador.png)

### Bitrate

Bitrate em um breve resumo seria o quanto de dados que você quer que transmita de você para o viewer.

![Bitrate](/assets/bitrate.png)

Mas como que eu posso saber quanto de bitrate eu preciso usar?

Simples, apenas vá em algum site de velocidade de internet e veja quantos mega de **upload** você tem.
1 mega = 1000 de bitrate.

Nesse site [aqui](https://stream.twitch.tv/encoding/) você consegue ver quantos de bitrate é necessário para cada resolução.

## Audio

Desde mais ou menos [novembro de 2020](https://help.twitch.tv/s/article/copyrighted-audio-warnings?language=pt_BR) a Twitch começou a dar strikes (avisos de direitos autorais) em canais que transmitem músicas sem autorização de autores/gravadoras.

O OBS tem uma solução simples para isso. Existe uma opção na parte de audio do OBS que você separa o audio que está sendo transmitido para seus viewers para a VOD (vod seria a gravação da sua live) que geralmente os avisos vem de vods, raramente você consegue tomar um strike ao vivo.

Em saida, marque a caixa _Faixa de VOD da Twitch_ e desmarque a track 6.

![Faixa de VOD da Twitch](/assets/configsaida.png)

Depois disso vá para sua tela inicial do OBS, e em Áudio do desktop, clique nos 3 pontos verticais e em seguida vá para _propiedades de audio avançadas_

![Propriedades de audio avançadas](/assets/trackaudio2.png)

Depois disso, desmarque a track 6 do seu Áudio do desktop

![Tracks de audio do desktop](/assets/trackaudio1.png)

## Teclas de atalho

O OBS oferece uma vasta opção de teclas de atalho para sua stream. Por exemplo, sua mãe invadiu sua live do nada? Aperte x e mute o microfone, ela apareceu no ângulo da câmera? Aperte y e esconda a câmera (as teclas que eu sei no exemplo são só demostrativas, você vai ter que configurar os atalhos para fazer isso).

![Teclas de Atalho](/assets/teclasAtalho.gif)

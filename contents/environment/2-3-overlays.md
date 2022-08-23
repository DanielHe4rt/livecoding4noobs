# Overlays para Streaming

## O que são overlays para streaming
Overlays podem ser considerados os widgets que a grande maioria dos streamers usam em suas lives. Alguns exemplos conhecidos
são o alert box e chat box.

Estes overlays geralmente são criados pelo Streamlabs e Streamelements, sendo assim, possuem seus próprios links e integrações
com seus softwares.
 
Nesta seção iremos abordar um pouco sobre as configurações dos overlays citados acima com um **foco maior na utilização
das ferramentas do streamlabs**, e futuramente em [configurando o ambiente](/contents/environment/2-4-setup.md)
iremos abordar a configuração de uma stream na totalidade juntando todos os passos presentes até o momento.

## Alert Box
O alert box visa mostrar na tela de transmissão - você pode colocar onde quiser e no tamanho que quiser - notificações
variadas em tempo real, sejam elas novos seguidores, novos inscritos, doações, raids, hosts, etc.

O alert box é equivalente ao overlay de event list, porém, funciona como uma espécie de notificação push, que desaparece
após um determinado tempo.

#### Como usar com o OBS:
1. Acesse [o site do streamlabs](https://streamlabs.com/), clique no canto superior esquerdo em "login" - as vezes este botão pode aparecer como "dashboard"
caso você já tenha feito login alguma vez -.
2. Na janela seguinte que irá abrir, procure no menu a esquerda a opção "alert box".
3. Você verá uma tela com finitas configurações - **vale a leitura com calma sobre cada configuração para ter um melhor aproveitamento do overlay** -.
4. Você encontrará quase no meio da tela uma barra chamada "Widget URL" e na sua direita um botão chamado "copy", clique nele e você terá
o link do seu alert box em seu copiar. **NÃO COMPARTILHE ESTE LINK COM NINGUÉM, ELE É REFERENTE SOMENTE A SUA LIVE**.
5. Após isso, vá ao seu OBS e procure a área de **fontes** - sources em inglês -.
6. Clique em adicionar e após isso selecione a opção **navegador** - browser em inglês -.
7. Após isso, ele abrirá uma janela e nessa janela você deverá dar um nome a sua fonte - você pode chamar do que preferir, normalmente é chamado de "alert box" -.
8. Uma nova janela irá aparecer e nela terá uma barra de endereço com nome "URL", lá deverá ser colocado o link que está no seu copiar.
9. Logo abaixo terão 2 configurações simples de altura e largura, geralmente as pessoas simplesmente deixam aquele valor de 800x600 e na tela de transmissão eles acertam corretamente o tamanho. - mais abaixo você verá algumas configurações avançadas, neste momento não entraremos a fundo nelas, mas caso queira, vale dar uma pesquisada sobre -.
10. Após tudo configurado, é só dar ok e ajeitar a notificação - aparecerá um quadrado vermelho em volta dela quando você clicar -, no mesmo lugar onde você pegou o link para o alert box haverá botões que simulam notificações, você pode apertá-los e conferir no seu OBS como a notificação fica, podendo então, aumentar ou diminuir o tamanho delas.
![gif](/assets/config-alertbox-obs.gif)


#### Como usar com o Streamlabs:
1. Com o streamlabs aberto, procure o sinal de " + " na janela sources.
2. Clique nele e após isso, selecione a opção "alert box" e depois "add source".
3. O programa pedirá para informar um nome a fonte - coloque o que preferir -.
4. Na janela seguinte, no menu a esquerda, terá opções do que você deseja que o alert box mostre, configure como preferir.
5. No canto superior direito possui o botão de "test widgets", para ter uma pré-visualização de como ficará seu alert box.
6. Após configurado, aperte no canto inferior direito em "done" e configure a posição que você deseja que o alert box apareça.
7. No caso do streamlabs, você pode testar as notificações diretamente no software, dando dois cliques na fonte.
![gif](/assets/config-alertbox-slabs.gif)

#


## Chat Box
O chat box visa abrilhantar e incluir mais o público ao streamer, com ele é possível mostrar as mensagens digitadas em chat
na tela da stream. Também é possível personalizar a estética das mensagens com html, css e js.

#### Como usar com o OBS:
1. Acesse [o site do streamlabs](https://streamlabs.com/), clique no canto superior esquerdo em "login" - as vezes este botão pode aparecer como "dashboard"
   caso você já tenha feito login alguma vez -
2. Na janela seguinte que irá abrir, procure no menu a esquerda a opção "all widgets".
3. Selecione o banner "chat box".
4. Na janela seguinte aparecerá a página de configurações do chat box, onde você pode optar por mostrar emojis nas mensagens, badges, e também personalizar o chat box com html, css e js.
5. Após configurado, procure a barra de "widget URL", e a direita dele terá o botão "copy", clicando nele, um link para adicionar o chat box a sua live será copiado. **NÃO COMPARTILHE ESTE LINK COM NINGUÉM, ELE É REFERENTE SOMENTE A SUA LIVE**.
6. Com o link copiado, vá ao OBS e procure a área de **fontes** - sources em inglês -.
7. Clique em adicionar e após isso selecione a opção **navegador** -browser em inglês -.
8. O OBS pedirá para adicionar um nome a fonte criada, você pode colocar o que preferir. Normalmente streamers colocam o nome "alert box".
9. Na janela seguinte que irá abrir, cole o link na barra de endereço com nome "URL".
10. Logo abaixo terão 2 configurações simples de altura e largura, geralmente os streamers deixam em 800x600 e ajeitam isso na própria preview do OBS.
11. Após isso, é só digitar algo no seu chat e ver se ficou do seu agrado no OBS.
![gif](/assets/config-chatbox-obs.gif)


#### Como usar com o Streamlabs:
1. Com o streamlabs aberto, procure o sinal de " + " na janela sources.
2. Clique nele e após isso, selecione a opção "chat box" e depois "add source". - o chat box fica um pouco mais abaixo na lista de itens -.
3. O programa irá pedir para informar um nome a fonte - coloque o que preferir -.
4. Na janela seguinte, no menu a direita, terá opções de configurações para o widget, configure como preferir.
5. Após configurar, pressione no canto inferior direito o botão "done" e pronto, seu chat bot estará adicionado.
![gif](/assets/config-chatbox-slabs.gif)

 [<- Integrações para Streaming (IMPORTANTE!)](/contents//basics/1-3-streaming-platforms.md) | [Inicio](/README.md) | [Integrações para Streaming (IMPORTANTE!) ->](/)
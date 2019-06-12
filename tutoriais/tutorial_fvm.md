#  TUTORIAL - Faça você mesmo (v1.0)
## Preparando o ambiente:
---------------------------------------------------------------------
1. Você vai precisar ter em mãos um computador e o dispositivo *FrescoGO* (com aquele cabo azul que acompanhá o dispositivo);
2. Baixe o software IDE Arduino, no endereço https://www.arduino.cc/en/Main/Software conforme o seu sistema operacional;
3. Faça a instalação do mesmo;
4. Após a instalação, baixe o driver para seu dispositivo em
https://www.driverscape.com/download/usb-serial-ch340; ou https://drive.google.com/file/d/0B2YXepPR2qlAdkR6eXNDMVU3a0E/view?usp=sharing;
5. Após baixar e clicar duas vezes logo se apresentará a tela abaixo:

![Instalador](http://i1.wp.com/blogdarobotica.com/wp-content/uploads/2016/05/executavel.png "Setup")

6. Basta apenas clicar na opção Install e pronto;
7. Conecte seu FrescoGo à porta USB do computador e verifique se irá reconhecer o dispositivo, se isso acontecer já estará tudo pronto para proceder a atualização, sempre que necessário.

<!-- Obs: http://blogdarobotica.com/instalando-driver-serial-para-arduinos-com-chip-ch340/
-->

## Efetuando atualização:
---------------------------------------------------------------------
1. Crie em seu computador uma pasta denominada "**frescoGO**" e baixe para a mesma os arquivos abaixo:
<https://github.com/eltonrios/FrescoGO_Up/blob/master/software/frescobol.ino>
<https://github.com/eltonrios/FrescoGO_Up/blob/master/software/serial.c.h> 
<https://github.com/eltonrios/FrescoGO_Up/blob/master/software/pt.c.h> 
<https://github.com/eltonrios/FrescoGO_Up/blob/master/software/tv.c.h> 
<https://github.com/eltonrios/FrescoGO_Up/blob/master/software/pitches.h> 
 
2. Entre nesta pasta e dê dois cliques no arquivo "**frescobol.ino**" e isso fará com que seja aberto o **IDE Arduino** e todo o pacote será carregado automaticamente;
3. Conecte seu dispositivo *FrescoGO* numa entrada USB do computador e observe se irá conectar e reconhecer o dispositivo (no rodapé da janela do aplicativo, lado direito, deverá aparecer algo como "Arduino Nano, ATmega328P (Old Bootloader) em COM12" (a porta COM, principalmente, pode variar);
4. Se até aí tudo correu bem, só falta agora enviar para seu dispositivo a nova programação, e para isso você vai clicar no icone de uma seta para a direita, que se encontra abaixo da opção "Arquivo", no menu principal;
5. Vai aparecer a palavra "Carregando..." na barra azul logo abaixo dos códigos, aguarde o processo ser concluído (normalmente dura de 15 a 30 segundos); 
6. Quando aparecer a palavra "Carregado." seu dispositivo já estará atualizado, podendo ser desconectado;

## Dicas:
---------------------------------------------------------------------
a. Pode acontecer de, após uma atualização, virem valores estranhos nos parâmetros de configuração, observe e parametrize se necessário;
b. 
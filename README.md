# RTSP_Tecvoz_Shinobi
RTSP config TecVoz TVZ 4 em 1 in Shinobi Video

![My Remote Image](https://http2.mlstatic.com/D_NQ_NP_744171-MLB54962136193_042023-O.webp?dl=0)

Para coletar os dados de um DVR Tecvoz TVZ Security 4 em 1 (similar ao acima) utilizando o protocolo RTSP no software Shinobi, utilize o seguinte padrão de URL:

`rtsp://DOMINIOouIP:PORTA/user=USUARIO&password=SENHA&channel=1&stream=0.sdp?`

Obs.:
- "channel" corresponde ao número do canal que você quer coletar do DVR. Exp.: DVR de 16 canais, use de 1 a 16 nesse campo.

Dica: Para facilitar, importe o JSON genérico na ferramenta, isso vai te poupar seu tempo ;)

[ENG]

To collect data from a Tecvoz TVZ Security 4 in 1 DVR using the RTSP protocol in the Shinobi software, use the following URL pattern:

`rtsp://DOMAINorIP:PORT/user=YOURUSER&password=YOURPASSWD&channel=1&stream=0.sdp?`

Note:
- "channel" corresponds to the channel number you want to collect from the DVR. Exp.: 16 channel DVR, change 1 to 16 in this field.

Tip: To make it easier, importing in the tool the generic JSON, it will save you time ;)

Referências/References:

https://condtec.com.br/linux/rtsp-de-dvr-lista-dos-principais-enderecos-rtsp/1099/

https://kerberosio.zendesk.com/hc/en-us/articles/208377905-RTSP-stream-of-IP-camera-is-not-working

https://suporte.monuv.com.br/pt-BR/articles/2885238-configuracao-e-teste-da-porta-rtsp

https://gist.github.com/alexishida/b804c0329e1a71d64336e1f0bcbd20da

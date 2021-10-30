# BLOQUEAR ATAQUE DE X-CONTENT-TYPE-OPTIONS NO .HTACCESS #

O X-Content-Type-Options permite que navegadores de suporte se protejam contra explorações de sniffing do tipo MIME. Isso é feito desativando o recurso 
de detecção de MIME do navegador e forçando-o a reconhecer o tipo de MIME enviado pelo servidor. Este cabeçalho é muito flexível, a implementação mais comum, 
segue o modelo abaixo.

# ATTACK BLOCKING OF CONTENT TYPE OPTIONS X NO .HTACCESS #

X-Content-Type-Options allows support browsers to protect themselves against MIME-type sniffing exploits. This is done by disabling the browser's MIME detection 
feature and forcing it to recognize the MIME type sent by the server. This header is very flexible, the most common implementation, follows the model below.

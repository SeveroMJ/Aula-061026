# Socket é o ponto de comunicação que um programa usa para enviar e receber dados pela rede. Ele é identificado pela combinação de um endereço IP e uma porta
#Uma comparação útil : se o endereço IP é o predio e a porta é o apartamento, o socket é a porta de entrada daquele apertamento. Toda conversa entre os dois programas na rede acontece entre oi dois sockets, um em cada ponta,

#    TCP    UDP
#Funcionamento - estabelece conexão antes de enviar dadps -- envia sem estabelecer conexão
#garantia de entrega -- sim e na ordem correta --- não
#velocidade -- menor ---maior
#exemplos de uso -- sites SSH FTP email --- DNS, STREAMING, JOGOS
#os pacotes são a conexão, as vezes o dowload quebra ou falha pq muitos pacotes tiveram erro, e isso pode ocasionar em "Erro no download" afinal a maioria se perdeu ou esta corrompidp 
#O socket é a base de tida comunicação em rede, vamos utilizar no curso para verificarse tal porta esta aberta, identificar serviços, desenvolvimento do portscanner, desenvolvimento do packet sniffer

#Requisições WEB --- são mensagens que um cliente envia a um servidor web pedindo um recurso ou uma ação, seguindo o protocole HTTP ou HTTPS, o servidor processa o pedido e devolve uma resposta, toda requisição conte
#Metodo: o tipo d eação
#URL: endereço do recuso
#Cabeçalho: informações adicionais, como o tipo de navegador cookies e credencias
#Corpo: dados enviados, como o conteudo de um formulario 

# GET --- SOLICITAR UM RECURSO COMO UMA PAGINA
#POST --- ENVIAR DADOS AO SERVIDOR COMO UM FORMULARIO DE LOGIN
#PUT - ATUALIZA UM RECURSO
#DELETE -REMOVER UM RECURSO
# HEAD - SOLICITAR APENAS OS CABEÇALHOS DA RESPOSTA DO CONTEUDO

#TODA RESPOSTA CONTEM UM CODIGO DE STATUS QUE INDICA O RESULTADO :

#2XX -- SUCESSO -- 200 OK
#3XX -- REDIRECIONAMENTO -- 301,302
#4XX -- ERRO DO CLIENTE -- 401 N AUTORIZADO , 403 PROIBIDO , 404 NÃO ENCONTRADO 
#5XX - ERRO DO SERVIDOR -- 500 ERRO INTERNO

# 



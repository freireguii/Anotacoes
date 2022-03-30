
# Anotações
Repositório com algumas anotações dos estudos realizados.

A internet foi criada em 1969, nos EUA. Levou o primeiro nome de Arpanet.

Um Cache é: ao se acessar um site, esse site deixa alguns dados pré-carregados no computador de quem o acessou, para carregar mais rápido futuramente.

Existem alguns protocólos, um deles é o HTTP (Hypertext Transfer Protocol) ele é um protocolo de comunicação, utilizado em sistemas de informação. A base do WWW.

Cookies são informações armazenadas pelos sites sobre o comportamento do usuário, são registros das atividades realizadas.
____________

# Rede:

Quando existir vários computadores necessitando acessar o internet, existirá a necessidade de um Backbone, logo, esse sistema nada mais é do que o responsável por realizar a ligação entre os vários computadores através de uma rede.

Geralmente quem disponibiliza o provedor de acesso são as empresas de telefonia, além disso, geralmente, um país detém um backbone -GERALMENTE.


O dns transforma o domínio em IP. E para se descobrir o IP de um domínio é necessário abrir o terminal e digital "ping + domínio do site".

OBS: existem domínios que não retornam com o IP, testei em alguns e não deu.

________

TCP (Transmission Control Protol)/IP (Internet Protocol)

O TCP/IP utiliza 4 camadas e cada camada é responsável por um grupo de tarefas, vide:
-1ª camada é a física (ex: uma placa de rede)
-2ªcamada é a de rede (ex: é o próprio protocolo de internet)
-3ª camada é a de transporte (ex: é o próprio TCP e o UDP)
-4ª camada é a de aplicação (ex: é a FTP, SMTP e a HTTP)

# Diferença entre o TCP e o UDP:

-O UDP não estabelece conexão, pois não realiza o famoso "HANDSHAKE" entre as máquinas, ele não precisa de nenhum tipo de confirmação de entrega; ele apenas envia os pacotes de dados, não se importando com quem irá receber, nem mesmo se houve de fato o recebimento. Dessa forma, o UDP (USER DATAGRAM PROTOCOL) utiliza bem menos largura de banda do que o TCP.

-O TCP (TRANSMISSION CONTROL PROTOCOL) estabelece uma conexão entre as máquinas, ele realiza o "HANDSHAKE', por isso é voltado para a realização de uma conexão de fato, há também a confirmação de entrega dos dados enviados, há uma busca pela integridade dos dados.

___

# PORTS:

Ao ocorrer a conexão entre duas máquinas, é necessário que se utilize as "portas", para tal conexão.

Cada conexão utilizará um tipo específico de "porta", haja vista que, cada protocolo, por exemplo, possui sua numeração específica. 

**Vejamos**: 
         -FTP 20 (File Transfer Protocol, transferência de arquivos)
         
         -SSH 22 (Porta utilizada para conexão entre duas máquinas, de forma segura para executar comandos)
         
         -SMTP 25 (Envio de e-mail, Simple Mail Transfer Protocol)
         
         -DNS 53 (traduz IP->NOME de Domínio e NOME de Domínio->IP  Domain Name System)
         
         -HTTP 80 (Hypertext Transfer Protocol)
         
         -HTTPS 443 (Hypertext Transfer Protocol Secure)
         
         -IMAP 993 (Internet Message Access Protocol, essa porta é a com segurança)
         
         -IMAP 143 (Internet Message Access Protocol, essa porta é a sem criptografia)
         
         -POP 995 (Post Office Protocol, essa porta é a com criptografia)
         
         -POP 110 (Post Office Protocol, essa porta é a sem segurança)
         
______________________________

POP3 (Post Office Protocol 3, também é utilizado para acessar um servidor de correio eletrônico, permite que todas as mensagens de e-mail contidas em uma caixa de entrada possam ser transferidas para outro serviço, em outro dispositivo, para que ele as organize)


O IMAP (Internet Message Access Protocol) e o POP (Post Office Protocol) são protocolos da Internet para o recebimento de email, eles realizam o download das mensagens do servidor do e-mail.
Já, o SMTP (Simple Mail Transfer Protocol) é um protocolo utilizado para enviar mensagens de e-mail.

______________________________


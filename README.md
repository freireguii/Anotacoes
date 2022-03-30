
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

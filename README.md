# ChatSocket

Chat multi usuários

Para usá-lo, primeiro é necessário rodar a classe servidor, para então rodar a classe cliente. 
Como é multi usuário, por que tem implementação de Threads, é possível rodar varias instancias da classe cliente.
Na classe cliente é possível configurar a máquina que está rodando o servidor, está por padrão como localhost, 
mas caso queira testar em alguma rede, é só alterar para o IP da máquina em que está o servidor.

Quando um usuário estiver conectado ao Servidor e quizer enviar uma mensagem para todos participantes, é só escrever a mensagem e enviar. 
Porém, caso queira enviar a mensagem de forma reservada à um único participante deve escrever a mensagem e no final digitar o caracter 
dois pontos  :  e o nome do cliente para quem irá enviar a mensagem, então ficaria assim > testando socket:marcio

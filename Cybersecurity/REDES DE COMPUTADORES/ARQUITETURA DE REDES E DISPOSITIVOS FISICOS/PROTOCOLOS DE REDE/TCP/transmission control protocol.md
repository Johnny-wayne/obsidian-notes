tcp = transmission control protocol

 
orientação a conexão - A aplicação envia um pedido de conexão para o destino e usa a conexão para transferir dados

garante uma transferencia de dados de maneira perfeita




conexão ponto a ponto - uma conexão tcp é estabelecida entre dois pontos.  A principio, pacotes de Broadcasting parecem violar esse principio, mas o que ocorre é que é enviado um pacote com um endereço especial em seu cabeçalho que qualquer computadores em sua rede pode responder a esse pacote, mesmo que e não esteja explicitamente endereçado a ele.



Confiabilidade - O TCP usa varias técnicas para proporcionar uma entrega confiável dos pacotes de dados que, dependendo da aplicação, gera uma grande vantagem que tem em relação ao UDP. aliado a outros fatores, o protocolo se mantem  bastante difundido nas redes de computadores. O TCP permite a recuperação de pacotes perdidos, a eliminação de pacotes duplicados, a recuperação de dados corrompidos e pode recuperar a ligação em caso de problemas no sistema e na rede.





FULL DUPLEX -  é possível transferência simultânea em ambas as direções (cliente - servidor) durante toda a sessão 





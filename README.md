este projeto foi interrompido pela metade, trata-se de um estudo sobre criptografia simétrica e assimétrica, sockets, whatsapp bot, api mercadopago, banco de dados (binary tree), entre outras idéias que surgiram durante o desenvolvimento como 'TokenGenerator.py'...

Oque é necessario para rodar?

1 - estar fora da regra cgnat (nat44) na sua provedora de internet (ou possuir ipv6 e ignorar passo 2, a não ser que queira link personalizado)
2 - possuir software "noip" atrelado a máquina hospedeira (o ip de acesso ao servidor derá o dns configurado no "noip")
3 - configurar "redirecionamento de portas/servidor virtual" no roteador para seu ip local (ex. 192.168.0.xxx) com a porta a ser utilizada
4 - configurar no roteador uma reserva no DHCP para o MAC address que vai hospedar o servidor
5 - configurar o arquivo "archives/config.txt" (mantenha ip igual a "0.0.0.0")
6 - executar a aplicação

obs: não há necessidade de executar o software como administrador,
fechar ou desativar antivírus ou usar cabo de rede ethernet!
# Projeto-Conceitual-E-COMMERCE

Entidades:
Cliente:
idCliente (PK)

nome

tipo (PJ ou PF)

Pagamento:

idPagamento (PK)

formaPagamento

detalhesPagamento

idCliente (FK)

Entrega:

idEntrega (PK)

status

codigoRastreio

idPedido (FK)

Pedido:

idPedido (PK)

dataPedido

idCliente (FK)

Relacionamentos:
Cliente 1:N Pagamento

Pedido 1:N Entrega
##########################################################################################################################################


Aqui esá um esquema de banco de dados conceitual vou deixar o arquivo para ver como ficou. 



# Projeto-Conceitual de banco de dados

Banco de dados E-COMMERCE
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

Banco de dados Sistema de Oficina Mecânica

Entidades:
Cliente:

idCliente (PK)

nome

endereco

telefone

Veiculo:

idVeiculo (PK)

placa

modelo

ano

idCliente (FK)

Mecanico:

idMecanico (PK)

nome

endereco

especialidade

OrdemServico:

idOS (PK)

dataEmissao

valor

status

dataConclusao

idVeiculo (FK)

idEquipe (FK)

Equipe:

idEquipe (PK)

nomeEquipe



Peca:

idPeca (PK)

descricao

valor

Relacionamentos:
Cliente 1:N Veiculo

Cliente 1:N OrdemServico

Equipe 1:N OrdemServico

Equipe N:M Mecanico (Relacionamento EquipeMecanico)

OrdemServico N:M Peca (Relacionamento OrdemServicoPeca)

# Projeto-Conceitual de banco de dados

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

Servico:

idServico (PK)

descricao

valorMaoDeObra

Peca:

idPeca (PK)

descricao

valor

Relacionamentos:
Cliente 1:N Veiculo

Veiculo 1:N OrdemServico

Equipe 1:N OrdemServico

Equipe N:M Mecanico (Relacionamento EquipeMecanico)

OrdemServico N:M Servico (Relacionamento OrdemServicoServico)

OrdemServico N:M Peca (Relacionamento OrdemServicoPeca)

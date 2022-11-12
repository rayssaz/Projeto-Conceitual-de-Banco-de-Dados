# Projeto-Conceitual-de-Banco-de-Dados
Desenvolvendo a primeira etapa da Modelagem de Banco de Dados, chamada de Projeto Conceitual, onde vamos analisar o problema e definir as entidades e objetos que devem ser criados, além do relacionamento entre eles. 

A ferramenta utilizada para a realização dessa tarefa é o MySQL WorkBench.

## Levantamento de Requisitos 
### Narrativa – Produto
 
* Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
* Cada produto possui um fornecedor;
* Um ou mais produtos podem compor um pedido

### Narrativa – Cliente
* O cliente pode se cadastrar no site com seu CPF ou CNPJ;
* O endereço do cliente irá determinar o valor do frete;
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

### Narrativa – Pedido
* Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
* Um produto ou mais compõem o pedido;
* O pedido pode ser cancelado.

### Narrativa – Fornecedor e Estoque


## Objetivo:
* Refinar o modelo apresentado acrescentando os seguintes pontos:
  -  Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
  -  Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
  - Entrega – Possui status e código de rastreio.

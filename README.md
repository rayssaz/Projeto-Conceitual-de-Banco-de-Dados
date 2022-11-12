# Projeto-Conceitual-de-Banco-de-Dados
Para iniciar a Modelagem de Banco de Dados, foi produzido um Projeto Conceitual a partir da narrativa fornecida. Desse modo, foram criadas todas as entidades, relacionamentos e atributos utilizando o MySQL WorkBench.

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
* Os fornecedores só podem ser a própria empresa, a que fornece os recursos e não os vendedores;
* Os produtos podem estar em estoques distintos e podemos ter uma quantidade diferente de produtos para o mesmo estoque. Podemos criar um relacionamento de quantidade entre o produto e o estoque.

## Objetivo:
* Refinar o modelo apresentado acrescentando os seguintes pontos:
  -  Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
  -  Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
  - Entrega – Possui status e código de rastreio.

DIO Desafio Projeto de Banco de Dados para um E-Commerce

Escopo:
Modelagem de um banco de dados para a venda de produtos em um E-commerce. A operação do negócio estabelece alguns requisitos para que o banco de dados atenda às suas necessidades. As entidades nesse contexto são: Cliente, Pedido, Produto, Estoque, Fornecedor, Terceiro fornecedor, Pagamento e Entrega.

- Narrativa

Cliente: O cliente pode se cadastrar no site com CPF ou CNPJ, mas não os dois ao mesmo tempo. O endereço do cliente irá determinar o valor do frete. Um cliente pode comprar mais de um pedido. Este tem um período de carência para a devolução do produto.

Pedido: Os pedidos são criados por clientes e possuem informações de compra, endereço, entrega (status e código de rastreio) e pagamento (podendo ter mais de uma forma). Um produto ou mais compoem o pedido. O pedido pode ser cancelado.

Produto: Os produtos são vendidos em uma única plataforma online. Eles podem estar disponíveis em estoque ou não. Contudo, estes podem ter vendedores distintos (terceiros). Cada produto possui um fornecedor. Um ou mais produtos podem compor um pedido.


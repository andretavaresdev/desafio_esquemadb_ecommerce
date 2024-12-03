# Projeto Lógico de Banco de Dados - Ecommerce

Este projeto apresenta a modelagem e implementação de um banco de dados para um sistema de e-commerce. Ele foi desenvolvido como parte de um desafio técnico, incluindo a estruturação das tabelas, inserção de dados de exemplo e criação de consultas SQL para extração de informações úteis.

Contexto
O cenário modelado corresponde a um sistema de e-commerce que abrange os seguintes pontos:

Clientes PJ e PF:
Um cliente pode ser Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas não ambos.

Formas de Pagamento:

Um pedido pode ter mais de uma forma de pagamento associada.

Entrega:

Cada pedido possui informações sobre status e código de rastreio.

Produtos, Fornecedores e Estoques:

Produtos estão associados a fornecedores e possuem estoques diferenciados por localidade.

O modelo lógico foi construído com base nas seguintes tabelas principais e seus relacionamentos:

Tabela |	Descrição

Cliente	| Armazena informações dos clientes, distinguindo entre PJ e PF.

Pedido |	Representa os pedidos realizados no e-commerce.

Produto |	Contém detalhes dos produtos vendidos.

Fornecedor |	Lista os fornecedores que abastecem o estoque de produtos.

Estoque |	Controla o estoque de produtos por localidade.

Pagamento |	Registra as formas de pagamento associadas aos pedidos.

Entrega	| Gerencia o status e código de rastreio das entregas dos pedidos.

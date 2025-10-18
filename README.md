# Projeto Banco de Dados E-Commerce

## Descrição
Este repositório contém a modelagem lógica de um banco de dados para um cenário de e-commerce. 
Inclui clientes (PF e PJ), produtos, fornecedores, pedidos, pagamentos e entregas.

## Estrutura do banco

- **Cliente**: Pessoa física ou jurídica.
- **Endereco**: Endereços de cobrança e entrega.
- **Fornecedor**: Empresas fornecedoras de produtos.
- **Produto**: Itens vendidos.
- **Pedido**: Pedidos realizados pelos clientes.
- **ItemPedido**: Detalhes dos produtos de cada pedido.
- **Pagamento**: Formas de pagamento de cada pedido.
- **Entrega**: Status e código de rastreio da entrega.

## Scripts SQL
1. **01_create_tables.sql**: Criação das tabelas e constraints.
2. **02_insert_data.sql**: Inserção de dados de teste.
3. **03_queries.sql**: Consultas complexas para análise.

## Diagrama EER
O diagrama EER está na pasta `diagrams/` como referência visual do modelo.

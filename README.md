# Diagrama de Banco de Dados para E-commerce

Este repositório contém o esboço de um diagrama de banco de dados para um sistema de e-commerce simples, incluindo entidades como Produto, Cliente, Pedido, Fornecedor, Estoque, Pagamento e Entrega.

## Estrutura do Banco de Dados

### Entidades:

1. **Produto**
   - ID do Produto
   - Nome do Produto
   - Descrição
   - Preço
   - Quantidade em Estoque
   - ID do Fornecedor

2. **Cliente**
   - ID do Cliente
   - Nome
   - Tipo de Cliente (PJ ou PF)
   - CPF (para Pessoa Física)
   - CNPJ (para Pessoa Jurídica)
   - Endereço
   - Contato

3. **Pedido**
   - ID do Pedido
   - ID do Cliente
   - Data do Pedido
   - Status do Pedido

4. **Fornecedor**
   - ID do Fornecedor
   - Nome do Fornecedor
   - Endereço do Fornecedor
   - Contato do Fornecedor

5. **Estoque**
   - ID do Produto
   - Quantidade em Estoque

6. **Pagamento**
   - ID do Pagamento
   - ID do Pedido
   - Método de Pagamento
   - Valor do Pagamento

7. **Entrega**
   - ID da Entrega
   - ID do Pedido
   - Status da Entrega
   - Código de Rastreio

### Relacionamentos:

- Cliente (Pedido) -> Relacionamento 1:N
- Produto (Estoque) -> Relacionamento 1:1
- Fornecedor (Produto) -> Relacionamento 1:N
- Pedido (Pagamento) -> Relacionamento 1:N
- Pedido (Entrega) -> Relacionamento 1:1

Este diagrama básico representa a estrutura do banco de dados para um sistema de e-commerce, permitindo a gestão de produtos, clientes, pedidos, fornecedores, estoque, métodos de pagamento e informações de entrega.

![DiagramaDIO](https://github.com/JuanVictorf/DiagramaDIOEcommerce/assets/68507832/281cfba6-893c-4d68-90ec-59ee6ec36099)


# ByteCard - Sistema de Gerenciamento de Cartões de Crédito

## Visão Geral
O ByteCard é um sistema de gerenciamento de cartões de crédito projetado para atender às necessidades dos gerentes de relacionamento. Ele permite o acompanhamento das compras dos clientes, oferecendo vantagens com base em seus perfis e movimentações.

## Principais Requisitos

### Listar Cartões
- Exibe todos os cartões cadastrados em uma tabela.
- Mostra informações como número do cartão, nome do cliente e limite.
- Permite ações como "Alterar limite", "Ver fatura", "Ativar" e "Cancelar" para cada cartão.

### Cadastrar Cartão
- Possui um botão para cadastrar um novo cartão.
- Apresenta um formulário com campos para limite e cliente.
- Gera automaticamente um número de cartão aleatório e define a validade.
   
### Ativar ou Cancelar Cartão
- Permite alterar o status de um cartão para "ATIVO" ou "CANCELADO".

### Cadastrar Compra
- Permite o cadastro de novas compras associadas a um cartão.
- O formulário inclui campos para o valor, categoria e estabelecimento da compra.

### Visualizar Fatura
- Permite ao usuário visualizar a fatura de um cartão em um mês específico.
- Exibe informações como número do cartão, cliente, valor total da fatura e lista de compras.

### Relatório de Gastos por Categoria
- Permite ao usuário visualizar a soma dos gastos de um cartão, agrupados por categoria, em um determinado mês.
- Apresenta uma tabela com categorias e valores gastos.

### Alterar Limite do Cartão
- Oferece a capacidade de alterar o limite de um cartão existente.

## Requisitos de Validação

### Validar Cadastro de Cartões
- Valida o formulário de cadastro de cartões, incluindo regras para o campo limite e cliente.

### Validar Cadastro de Compra
- Valida o formulário de cadastro de compras, incluindo regras para os campos cartão, valor, categoria e estabelecimento.

## Requisitos Não Funcionais

### Acessibilidade
- Deve atingir um índice de acessibilidade de 90% ou superior no Lighthouse (Chrome -> Developer Tools -> Lighthouse).

## Restrições Arquiteturais

### Tecnologias Utilizadas
- Python 3
- SGBD MySQL
- Flask

Este documento fornece um resumo dos principais requisitos do projeto ByteCard. Para detalhes completos sobre cada requisito, consulte a documentação completa do projeto.

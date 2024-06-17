# ALP - Finanças

Um software para controle de estoque, controle financeiro e outras coisas

## Histórias de usuários

-   [ ] O Usuário podera fazer login no site e ter acesso ao dashboard.
-   [ ] O Usuário poderá cadastrar um cliente novo.
-   [ ] O Usuário poderá efetuar uma compra.
-   [ ] O Usuário poderá cadastrar um produto em estoque.

## Requisitos do Software

### Requisitos Funcionais:
- **Autenticação:**
    - O sistema deve permitir que um usuario consiga acessar o painel.

- **Controle de Estoque**
    - O sistema deve permitir a adição de novos itens ao estoque.
    - O sistema deve permitir a atualização de itens existentes no estoque.
    - O sistema deve permitir a remoção de itens do estoque.
    - O sistema deve permitir a visualização do estado atual do estoque.

- **Vendas:**
    - O sistema deve permitir a criação de uma nova venda.
    - O sistema deve permitir a adição de itens a uma venda.
    - O sistema deve permitir a remoção de itens de uma venda.
    - O sistema deve calcular automaticamente o total da venda com base nos itens adicionados.
    - O sistema deve atualizar o estoque após a conclusão de uma venda.

- **Clientes:**
    - O sistema deve permitir a criação de um novo cliente.
    - O sistema deve perguntar na criação de uma nova venda se é para um cliente que ja existe.
    - O sistema deve verificar se um cliente esta devendo algo.

- **Compras Parceladas:**
    - O sistema deve permitir a criação de uma nova compra parcelada.
    - O sistema deve permitir a definição do número de parcelas para uma compra.
    - O sistema deve rastrear o pagamento de cada parcela.
    - O sistema deve atualizar o estoque após a conclusão de uma compra parcelada.

### Requisitos Não Funcionais:
- **Desempenho:** O sistema deve ser capaz de processar transações de forma rápida e eficiente.
- **Segurança:** O sistema deve proteger os dados sensíveis dos usuários.
- **Usabilidade:** O sistema deve ser fácil de usar, com uma interface intuitiva.
- **Confiabilidade:** O sistema deve ser confiável, com mínimas interrupções de serviço.
- **Manutenibilidade:** O sistema deve ser fácil de modificar e atualizar.


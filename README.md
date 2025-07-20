# Refund

Sistema de solicitação de reembolso desenvolvido em JavaScript puro, HTML e CSS. Permite aos usuários cadastrar despesas por categoria, visualizar o total gasto e gerenciar suas solicitações de reembolso.

## Objetivo

O projeto visa facilitar o processo de solicitação de reembolso de despesas, oferecendo uma interface intuitiva para cadastro e acompanhamento de gastos por categoria. Ideal para empresas e organizações que precisam gerenciar reembolsos de funcionários.

## Tecnologias Utilizadas

- **HTML5** - Estrutura semântica da aplicação
- **CSS3** - Estilização responsiva com Flexbox
- **JavaScript (Vanilla)** - Lógica de negócio e manipulação do DOM
- **Google Fonts** - Tipografia Open Sans
- **SVG** - Ícones e elementos gráficos

## Instalação e Execução

1. Clone o repositório:

```bash
git clone [url-do-repositorio]
cd Refund
```

2. Abra o arquivo `index.html` em seu navegador:

```bash
# Opção 1: Duplo clique no arquivo index.html
# Opção 2: Use um servidor local
```

3. Acesse `http://localhost:8000` (se usando servidor local)

## Funcionalidades

- **Cadastro de despesas** com nome, categoria e valor
- **Formatação automática** de valores em Real (R$)
- **Categorização** por tipo (Alimentação, Hospedagem, Serviços, Transporte, Outros)
- **Lista dinâmica** de despesas cadastradas
- **Cálculo automático** do total gasto
- **Remoção** de itens da lista
- **Interface responsiva** para diferentes tamanhos de tela

## Estrutura do Projeto

```
Refund/
├── index.html          # Página principal
├── styles.css          # Estilos da aplicação
├── scripts.js          # Lógica JavaScript
└── img/               # Ícones e imagens
    ├── logo.svg
    ├── food.svg
    ├── accommodation.svg
    ├── services.svg
    ├── transport.svg
    ├── others.svg
    ├── remove.svg
    └── chevron-down.svg
```

## Padrões de Desenvolvimento

- **JavaScript Modular**: Funções organizadas por responsabilidade
- **CSS Responsivo**: Design adaptável com media queries
- **HTML Semântico**: Estrutura clara e acessível
- **Formatação de Moeda**: Implementação nativa com `toLocaleString()`

## Observações

- O projeto não utiliza frameworks ou bibliotecas externas
- Não requer build ou compilação
- Funciona diretamente no navegador
- Dados são armazenados apenas em memória (não há persistência)
- Compatível com navegadores modernos

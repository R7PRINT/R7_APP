# Documentação do R7 Print

## Visão Geral

O R7 Print é um sistema de gestão completo para empresas gráficas, desenvolvido com base no Holdprint. O aplicativo oferece funcionalidades para gerenciamento de clientes, fornecedores, produção, financeiro, estoque e muito mais, tudo com uma interface moderna e intuitiva.

## Tecnologias Utilizadas

- **Frontend**: Next.js, React, Tailwind CSS
- **Gerenciamento de Estado**: React Hooks
- **Estilização**: Tailwind CSS
- **Componentes**: Componentes personalizados reutilizáveis

## Estrutura do Projeto

```
r7-print/
├── src/
│   ├── app/
│   │   ├── dashboard/
│   │   │   ├── cadastros/
│   │   │   ├── custeio/
│   │   │   ├── producao/
│   │   │   ├── financeiro/
│   │   │   ├── estoque/
│   │   │   ├── relatorios/
│   │   │   ├── ajustes/
│   │   │   ├── suporte/
│   │   │   └── page.js
│   │   ├── login/
│   │   │   └── page.js
│   │   ├── layout.js
│   │   └── page.js
│   ├── components/
│   │   ├── forms/
│   │   ├── layout/
│   │   └── ui/
│   └── lib/
│       └── auth/
├── public/
└── package.json
```

## Módulos Principais

### 1. Dashboard

O dashboard principal apresenta uma visão geral do negócio, com indicadores financeiros, gráficos de desempenho e lista de jobs em andamento.

### 2. Cadastros

#### 2.1 Clientes
- Cadastro completo de clientes
- Listagem com busca e filtros
- Edição e exclusão de registros

#### 2.2 Fornecedores
- Cadastro completo de fornecedores
- Listagem com busca e filtros
- Edição e exclusão de registros

### 3. Custeio

#### 3.1 Centros de Custo
- Gerenciamento de centros de custo
- Alocação de despesas

#### 3.2 Equipamentos
- Cadastro de equipamentos
- Controle de depreciação

#### 3.3 Processos
- Definição de processos produtivos
- Parametrização de custos

#### 3.4 Produtos e Serviços
- Cadastro de produtos e serviços
- Definição de preços e margens
- Categorização

#### 3.5 Terceirizados
- Gestão de serviços terceirizados
- Controle de custos externos

### 4. CRM

- Gestão de relacionamento com clientes
- Histórico de interações
- Oportunidades de negócio

### 5. Produção

#### 5.1 Acompanhamento
- Visão geral dos jobs em produção
- Status e prazos

#### 5.2 Jobs
- Cadastro detalhado de jobs
- Definição de especificações
- Controle de prazos e prioridades

#### 5.3 Terminal de Produção
- Acompanhamento em tempo real
- Registro de produção

#### 5.4 Gerenciamento e Planejamento
- Planejamento de produção
- Alocação de recursos

### 6. Financeiro

#### 6.1 Contas a Pagar
- Registro de despesas
- Controle de vencimentos
- Baixa de pagamentos

#### 6.2 Contas a Receber
- Registro de receitas
- Controle de recebimentos
- Baixa de pagamentos

#### 6.3 Despesas Fixas
- Cadastro de despesas recorrentes
- Projeção financeira

#### 6.4 Central de Movimentações
- Visão consolidada de movimentações
- Fluxo de caixa

#### 6.5 Notas Fiscais
- Emissão e controle de notas fiscais
- Integração com sistemas fiscais

### 7. Estoque

#### 7.1 Matéria Prima
- Cadastro de itens
- Controle de estoque mínimo
- Alertas de reposição

#### 7.2 Pedidos de Compra
- Geração de pedidos
- Acompanhamento de entregas

#### 7.3 Movimentações de Estoque
- Registro de entradas e saídas
- Histórico de movimentações

#### 7.4 Central de Estoque
- Visão consolidada do estoque
- Valorização de inventário

### 8. Relatórios

- Relatórios financeiros
- Relatórios de vendas
- Relatórios gerenciais

### 9. Ajustes

- Configurações do sistema
- Gerenciamento de usuários
- Personalização

### 10. Suporte

- Chat de suporte
- Base de conhecimento
- Perguntas frequentes

## Funcionalidades Principais

### Autenticação
- Login seguro
- Controle de sessão
- Níveis de acesso

### Gestão de Clientes e Fornecedores
- Cadastro completo
- Histórico de interações
- Documentos relacionados

### Gestão de Produção
- Fluxo completo de jobs
- Acompanhamento de status
- Controle de prazos

### Gestão Financeira
- Contas a pagar e receber
- Fluxo de caixa
- Relatórios financeiros

### Gestão de Estoque
- Controle de matéria prima
- Movimentações
- Alertas de estoque mínimo

## Guia de Uso

### Login
1. Acesse a página de login
2. Insira suas credenciais
3. Clique em "Entrar"

### Navegação
- Use o menu lateral para acessar os diferentes módulos
- O dashboard apresenta uma visão geral do negócio
- Cada módulo possui funcionalidades específicas

### Cadastros
1. Acesse o módulo desejado
2. Clique em "Novo" para adicionar um registro
3. Preencha os campos obrigatórios
4. Clique em "Salvar"

### Produção
1. Crie um novo job
2. Defina as especificações
3. Acompanhe o status pelo módulo de Acompanhamento
4. Atualize o progresso pelo Terminal de Produção

### Financeiro
1. Registre contas a pagar e receber
2. Realize baixas de pagamentos
3. Acompanhe o fluxo de caixa pela Central de Movimentações

### Estoque
1. Cadastre itens de matéria prima
2. Registre entradas e saídas
3. Monitore níveis de estoque
4. Gere pedidos de compra quando necessário

## Considerações Finais

O R7 Print foi desenvolvido para atender às necessidades específicas de empresas gráficas, oferecendo um conjunto completo de ferramentas para gestão do negócio. A interface intuitiva e as funcionalidades abrangentes permitem um controle eficiente de todos os aspectos da operação.

# 💻 TECH SOFTWARE

**Sistema de gerenciamento de atividades acadêmicas e comunicação entre alunos e professores.**

O TECH SOFTWARE é um projeto de desenvolvimento de software criado pela **Equipe Alfa**, com o objetivo de facilitar a organização das atividades escolares, auxiliar professores no gerenciamento de tarefas e aproximar alunos e professores por meio de um sistema de comunicação.

---

## 🎯 Objetivo do projeto

Desenvolver uma aplicação web que facilite a rotina acadêmica por meio de ferramentas de organização, gerenciamento de atividades e comunicação entre estudantes e professores.

O projeto será desenvolvido como um MVP (Minimum Viable Product), priorizando as funcionalidades essenciais.

## 🚀 Funcionalidades principais

### 1. Sistema de urgência das atividades
- Visualização das atividades cadastradas.
- Identificação dos prazos de entrega.
- Classificação visual dos níveis de urgência.
- Ordenação das atividades conforme a proximidade da entrega.

### 2. Cadastro de atividades
- Cadastro de atividades pelos professores.
- Formulário com validação de informações.
- Armazenamento dos dados no Supabase.
- Exibição das atividades cadastradas.

### 3. Comunicação entre aluno e professor
- Visualização de conversas.
- Envio e recebimento de mensagens.
- Histórico de comunicação.
- Armazenamento das mensagens no Supabase.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Finalidade |
|---|---|
| React | Construção da interface |
| Vite | Ambiente de desenvolvimento |
| JavaScript | Lógica da aplicação |
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização e responsividade |
| Supabase | Banco de dados e autenticação |
| Git | Controle de versão |
| GitHub | Hospedagem e colaboração |

---

## 📁 Estrutura de pastas

```text
TECH-SOFTWARE/
│
├── public/
│   ├── images/
│   └── favicon.ico
│
├── src/
│   ├── assets/
│   │   ├── images/
│   │   └── icons/
│   │
│   ├── components/
│   │   ├── Header/
│   │   ├── Footer/
│   │   ├── ActivityCard/
│   │   ├── ActivityForm/
│   │   ├── Chat/
│   │   └── Button/
│   │
│   ├── pages/
│   │   ├── Home/
│   │   ├── Activities/
│   │   ├── RegisterActivity/
│   │   └── Messages/
│   │
│   ├── context/
│   ├── hooks/
│   ├── services/
│   ├── styles/
│   ├── utils/
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── .env.example
├── .gitignore
├── index.html
├── package.json
└── README.md
```

### Organização do código

- **components:** componentes reutilizáveis da interface.
- **pages:** páginas principais da aplicação.
- **assets:** imagens e ícones.
- **context:** gerenciamento de estados globais.
- **hooks:** hooks personalizados do React.
- **services:** integração com o Supabase.
- **styles:** estilos globais.
- **utils:** funções auxiliares e validações.

---

## ⚙️ Instalação e execução

### Pré-requisitos
- Node.js instalado.
- npm instalado.
- Git instalado.
- Conta no GitHub.
- Projeto configurado no Supabase.

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acessar a pasta

```bash
cd tech-software
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Configurar as variáveis de ambiente

Criar um arquivo `.env` na raiz do projeto:

```env
VITE_SUPABASE_URL=sua_url_do_supabase
VITE_SUPABASE_ANON_KEY=sua_chave_publica
```

Não compartilhe chaves secretas ou credenciais administrativas. O arquivo `.env` não deve ser enviado ao GitHub.

### 5. Executar o projeto

```bash
npm run dev
```

---

## 🗄️ Integração com Supabase

O Supabase será utilizado como backend da aplicação, oferecendo:

- Banco de dados PostgreSQL.
- Autenticação de usuários.
- Gerenciamento de perfis.
- Armazenamento de atividades.
- Armazenamento de mensagens.
- Controle de acesso utilizando Row Level Security (RLS).

A comunicação com o Supabase será centralizada na pasta `services/`.

---

## 👥 Equipe de desenvolvimento — Equipe Alfa

| Integrante | Função |
|---|---|
| Alex França | Product Owner |
| Luis Vinicius | UX/UI Designer |
| Miguel Soares | Desenvolvedor Front-end 1 |
| Lorenzo Guedes | Desenvolvedor Front-end 2 |
| Julio César | Desenvolvedor Back-end |

---

## 📋 Gerenciamento do projeto

A organização e o acompanhamento das tarefas serão realizados pelo Trello, utilizando as seguintes etapas:

- Backlog
- A fazer
- Em andamento
- Revisão e testes
- Concluído

As tarefas possuem descrições, checklists e critérios de conclusão.

---

## 📐 Requisitos de qualidade

- Interface responsiva.
- Acessibilidade e boa legibilidade.
- Carregamento da tela principal em até 3 segundos.
- Segurança dos dados utilizando RLS no Supabase.
- Mensagens claras para erros e estados vazios.
- Autenticação e permissões conforme os perfis dos usuários.

---

## 🎓 Objetivo final

Entregar um MVP funcional, organizado e responsivo, demonstrando como a tecnologia pode contribuir para melhorar a organização acadêmica e a comunicação no ambiente escolar.

**TECH SOFTWARE — Equipe Alfa.**

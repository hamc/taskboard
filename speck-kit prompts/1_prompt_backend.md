# 1.  Backend

## Constituição

Crie a **Constituição** de um sistema web chamado **TaskBoard**.

O sistema deve ser **desenvolvido em Python**, utilizando o **FastAPI** como framework web e o **SQLite** como banco de dados.

O **TaskBoard** tem como objetivo gerenciar **projetos e tarefas**, oferecendo operações **CRUD** por meio de uma **API REST**.

A Constituição deve incluir:

- **Missão do sistema**
- **Domínio e escopo**
- **Entidades principais**
- **Diretrizes técnicas**
  - Arquitetura
  - Convenções de código
  - Boas práticas
- **Princípios de desenvolvimento**
- **Padrões de documentação**

Toda a documentação deve ser escrita **em português**.

## Spec

Versao inicial

Escreva a **Spec** do módulo de **gerenciamento de tarefas**.

A spec deve definir:

- **Objetivo do módulo**
- **Entidades envolvidas**
- **Endpoints REST** (método, caminho, entrada, saída)
- **Regras de validação**
- **Dependências** (ex.: banco de dados, módulos internos)
- **Exemplos de payloads (request/response)**

Use **formato YAML** compatível com o **Spec-Kit**, mantendo clareza e consistência com o restante do sistema.

O foco é **apenas o backend** neste momento.

## Plan

Com base na **Constituição** e na **Spec** do módulo de tarefas do TaskBoard, gere um **plano de implementação** em **Python com FastAPI**.

O plano deve incluir:

- **Arquivos a serem criados**
  - Nome e função de cada arquivo
- **Exemplos de código** para as principais partes
- **Passos de execução** do projeto
- **Comandos para rodar localmente**

O resultado deve ser **direto e estruturado em YAML**, mostrando claramente o que será necessário para implementar o **backend** do módulo de tarefas.

# 2. Frontend

## Constituição

Expanda a **Constituição** do sistema **TaskBoard**, adicionando um **frontend moderno**.

O sistema já possui um **backend** desenvolvido em **Python com FastAPI** e **SQLite**, responsável pelas operações de API REST.

Agora, defina o **frontend**, que será responsável por oferecer uma interface web simples, intuitiva e moderna para o gerenciamento de projetos e tarefas.

**Requisitos técnicos:**

- Desenvolvido em **Node.js**, com a versão gerenciada via **ASDF**
- Framework de interface: **Next.js (React)**
- Estilização com **TailwindCSS**
- Comunicação com o backend via **Axios**
- Build e gerenciamento de pacotes com **npm**
- Configuração de variáveis de ambiente (`.env.local`) para definir a URL base da API

**Características desejadas:**
- Layout limpo e responsivo
- Funcionalidades:
  - Listagem de tarefas
  - Criação, edição e exclusão de tarefas
  - Indicação visual do status (pendente, concluída)
- Documentação e textos em **português**
- Boas práticas de integração com o backend:
  - Tratamento de erros e estados de carregamento
  - Estrutura organizada de componentes (`pages/`, `components/`, `services/`)

Inclua na Constituição:
- Missão e papel do frontend dentro do sistema
- Diretrizes de design e usabilidade
- Princípios de arquitetura e convenções de código
- Padrões de comunicação com a API REST


## Spec

Com base na Constituição do TaskBoard, escreva a **Spec** do **frontend**.

O frontend deve oferecer uma **interface simples e moderna** para interagir com o backend FastAPI, permitindo visualizar e gerenciar tarefas.

Defina os seguintes pontos:

- **Objetivo:**  
  Permitir que o usuário visualize, crie e exclua tarefas de forma fácil e intuitiva.

- **Principais páginas e componentes:**  
  - Página inicial: lista de tarefas.  
  - Formulário simples: criar nova tarefa.  
  - Botões para excluir tarefas.  

- **Tecnologias utilizadas:**  
  - **Node.js (via ASDF)**  
  - **Next.js (React)**  
  - **TailwindCSS** para o layout  
  - **Axios** para comunicação com o backend

- **Integração:**  
  O frontend deve consumir os endpoints REST do backend FastAPI, definidos anteriormente, utilizando a URL configurada em variável de ambiente (`NEXT_PUBLIC_API_URL`).

- **Regras básicas:**  
  - Exibir mensagens de sucesso ou erro  
  - Atualizar a lista automaticamente após criar ou excluir uma tarefa  
  - Interface e textos sempre em **português**

## Plan

Com base na Constituição e na Spec do frontend do TaskBoard, gere um **plano de implementação simples** em **Next.js** com **TailwindCSS** e **Axios**.

O plano deve incluir:

- **Arquivos principais:**
  - `pages/index.tsx`: página inicial com listagem e formulário.  
  - `services/api.ts`: responsável pelas chamadas à API.  

- **Etapas principais:**
  1. Instalar o Node.js com o ASDF.  
  2. Criar o projeto com `npx create-next-app taskboard-frontend`.  
  3. Instalar `axios` e `tailwindcss`.  
  4. Configurar o Tailwind.  
  5. Criar os componentes e conectar ao backend.  
  6. Informar como executar localmente o backend e frontend para acesso do usuário.

O objetivo é permitir que os alunos **visualizem rapidamente o fluxo completo** entre frontend e backend, sem entrar em detalhes avançados de código.

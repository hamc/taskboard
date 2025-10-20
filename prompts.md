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

Expanda a **Constituição do sistema TaskBoard**, incluindo um **frontend moderno**.

O sistema já possui um **backend** desenvolvido em **Python com FastAPI** e **SQLite**, responsável pelas operações de API REST.

Agora, o objetivo é criar o **frontend** do TaskBoard, com as seguintes características:

- Desenvolvido em **Node.js**, utilizando um framework moderno de interface (por exemplo: **Next.js**, **React** ou **SvelteKit**)
- Gerenciamento da versão do Node feito via **ASDF**
- Interface **simples, porém moderna**, voltada à produtividade
- Deve se comunicar com o backend existente por meio das rotas REST já definidas
- Toda a documentação e mensagens devem permanecer **em português**

A Constituição deve incluir:
- Missão e papel do frontend dentro do sistema
- Diretrizes de design e usabilidade
- Estrutura básica de pastas e organização do código
- Boas práticas de integração com o backend (ex.: uso de variáveis de ambiente, fetch/axios, tratamento de erros)

## Spec

Com base na **Constituição estendida do TaskBoard**, escreva a **Spec do módulo de frontend**.

Defina:

- **Objetivo do frontend**
- **Páginas e componentes principais**
- **Fluxos de navegação e interações com o backend**
- **Estrutura de pastas sugerida**
- **Dependências principais** (framework, bibliotecas, ferramentas de build)
- **Comandos básicos de execução e build**
- **Exemplo de payloads** consumidos das APIs

Use formato **YAML compatível com o Spec-Kit** e mantenha a documentação em **português**.


## Plan

Com base na **Constituição** e na **Spec do módulo de frontend do TaskBoard**, gere um **plano de implementação**.

O plano deve incluir:

- **Arquivos e pastas** a serem criados
  - Exemplo: `pages/`, `components/`, `services/`
- **Trechos de código de exemplo**
  - Incluindo chamada de API para listar tarefas
- **Passos de execução**
  - Instalação via **ASDF**
  - Comandos `npm install`, `npm run dev`, etc.
- **Integração com o backend existente**
  - URL base configurável via variável de ambiente

O plano deve ser **direto e estruturado em YAML**, voltado para o desenvolvimento local e com foco em uma interface **simples, responsiva e moderna**.

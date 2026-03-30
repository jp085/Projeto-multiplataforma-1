## Inven
Inven é uma proposta de plataforma digital voltada para auxiliar empreendedores. A aplicação permitirá que empreendedores, micro e pequenos empresários realizem controle de estoque, contagem de inventário e entre outras funcionalidades para com seu empreendimento.

---

## Sumário

- [Inven](#Inven)
- [Descrição](#descrição)
- [Problema Abordado e Justificativa](#problema-abordado-e-justificativa)
- [Conexão com o ODS 11](#conexão-com-o-ods-11)
- [Objetivos do Sistema](#objetivos-do-sistema)
- [Escopo do Projeto](#escopo-do-projeto)
- [Visão Geral da Arquitetura (com diagrama)](#visão-geral-da-arquitetura-com-diagrama)
- [Tecnologias Propostas](#tecnologias-propostas)
- [Cronograma para Etapa 2 (Implementação do Projeto)](#cronograma-para-etapa-2-implementação-do-projeto)
- [Integrantes da Equipe e Seus Papéis](#integrantes-da-equipe-e-seus-papéis)
- [Documentos Complementares](#documentos-complementares)

  ---

## Descrição

Muitas vezes, empreendedores tem certas dificuldades com o seu negócio principalmente em relação aos seus materiais, muitos deles não tem um controle acerca do que entrou e oque saiu, assim tendo dificuldades em realizar seus cálculos do negócio.
---

## Problema Abordado e Justificativa

Atualmente, esses empreendedores enfrentam inconsistências no seu negócio devido a falta de registros e controle de estoque, controle de custo e entre outros pontos referentes ao comércio, com isso pensamos no Inven, um sistema para auxiliar eles a resolverem ou organizarem melhor suas atividades de empreendedores. 

---

## Conexão com o ODS 11
O projeto Inven contribui diretamente para o Objetivo de Desenvolvimento Sustentável 11 — Cidades e Comunidades Sustentáveis — o Inven permite que os empreendedores tenham mais controle de suas finanças e custos, assim melhorando seus preços praticados e evitando grandes perdas para o seu negócio.

---

## Objetivos do Sistema

Objetivo Geral: Desenvolver uma aplicação multiplataforma que permita o cadastro, consulta, atualização e rastreabilidade dos insumos gerais do empreendimento.

Objetivos Específicos:

- Criar uma API RESTful para gerenciamento de usuários e empreendimentos

- Implementar autenticação segura via JWT

- Disponibilizar filtros de busca por código e palavras-chave

- Planejar interfaces para web e dispositivos móveis

- Garantir estrutura de testes automatizados desde o início

---

## Escopo do Projeto

O escopo do Inven abrange o desenvolvimento de uma aplicação multiplataforma composta por backend (API RESTful em PHP), banco de dados SQL (MySql), integração com serviços externos (Caso haja necessidade), e frontend web/mobile responsivo.  
O sistema permitirá o cadastro, consulta, edição e exclusão de materiais, controle de avarias, registro de venda (forma de pagamento).
Estão fora do escopo, nesta etapa, funcionalidades de bipagem, pagamentos online ou gestão financeira dos empreendimentos.

---

## Visão Geral da Arquitetura (com diagrama)

Arquitetura prevista:

- Comunicação via protocolo HTTP

- Autenticação baseada em JWT

- Banco de dados SQL com MySQL

- API para sistemas externos

---

## Tecnologias Propostas

### Backend
- **PHP** — ambiente de execução backend
- **Express.js** — framework para rotas e middlewares
- **MySQL** — banco de dados SQL
- **JWT** — autenticação segura
- **Jest + Supertest** — testes automatizados
- **Dotenv** — gerenciamento de variáveis de ambiente

### Frontend
- **HTML5** — estruturação das páginas
- **CSS3** — estilização e responsividade
- **JavaScript (ES6+)** — interatividade e integração com a API

---

## Cronograma para Etapa 2 (Implementação do Projeto)

A Etapa 2 será dedicada à implementação prática do projeto Inven, contemplando o desenvolvimento do backend e frontend da aplicação. O cronograma abaixo distribui as atividades por semana, considerando a complexidade técnica e a colaboração entre os integrantes da equipe:

| Semana | Atividades                                                                 |
|--------|-----------------------------------------------------------------------------|
| 1      | Configuração inicial do repositório, estrutura de pastas e variáveis de ambiente |
| 2      | Desenvolvimento do backend: rotas, controllers, models, serviços e autenticação |
| 3      | Implementação dos testes automatizados |
| 4      | Início do frontend: estruturação das páginas com HTML e CSS responsivo     |
| 5      | Adição de interatividade com JavaScript |
| 6      | Validação técnica, ajustes finais, documentação complementar e entrega do projeto |

## Integrantes da Equipe e Seus Papéis
O projeto será desenvolvido por uma equipe de seis integrantes, com divisão clara de responsabilidades desde o planejamento. Cada membro atuará em áreas específicas do backend e frontend, garantindo organização, rastreabilidade e colaboração eficiente.

### João Paulo Gomes dos Santos

**Função:** Líder Técnica e Desenvolvedora Principal 

**Responsabilidades Planejadas:**

- Definição da arquitetura da API e estrutura de pastas

- Implementação das rotas de empreendimentos (controller, model, validações)

- Criação do middleware de autenticação com JWT

- Desenvolvimento da API para comunicação com outros sistemas

- Estruturação dos arquivos principais do servidor (index, dotenv)

- Organização da documentação técnica e do README

- Apoio na estruturação do frontend (HTML base e organização das seções)

### THAMIRES GUEDES MOURA LOPES
**Função:** Autenticação e Segurança

**Responsabilidades Planejadas:**

- Implementação do controller de usuários (cadastro e login)

- Configuração da conexão com o banco de dados MySql

- Validação de tokens JWT e proteção de rotas

- Apoio na criação da página de login no frontend

### PAULO RAFAEL BAIMA CAVALCANTE

**Função:** Integração com Serviços Externos

**Responsabilidades Planejadas:**

- Apoio no desenvolvimento das API para comunicação com outros sistemas

- Implementação dos controllers e rotas externas

- Apoio na criação de logs de chamadas das API

### ----

**Função:** Documentação Técnica e Estrutura de Rotas 

**Responsabilidades Planejadas:**

- Redação da documentação técnica da arquitetura da API

- Organização das rotas de usuários e autenticação

- Apoio na estruturação das páginas de cadastro e navegação no frontend

### ---

**Função:** Modelagem de Dados e Validações

**Responsabilidades Planejadas:**

- Definição dos schemas de usuário e empreendimento

- Implementação das regras de validação e criptografia de senha

- Sugestões de tratamento de erros e mensagens no backend

- Apoio na validação de formulários no frontend (JavaScript)

### ---

**Função:** Testes e Validação Técnica

**Responsabilidades Planejadas:**

- Estruturação dos testes automatizados com Jest e Supertest

- Testes manuais das rotas públicas e protegidas

- Validação das respostas da API e integração com o frontend

- Apoio na criação de scripts de teste e simulação de uso.

---

## Documentos Complementares

- [Requisitos do Sistema](./docs/requirements/requirements.md)
- [Arquitetura do Sistema](./docs/architecture/architecture.md)
- [Modelo de Dados](./docs/database/database_model.md)
- [Especificação da API](./docs/api/api_specification.md)
- [Protótipos Web](./prototypes/web)
- [Protótipos Mobile](./prototypes/mobile)

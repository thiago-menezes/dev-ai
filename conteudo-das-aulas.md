# Conteúdo das Aulas - Estrutura Completa

## Estrutura Modular

```
📦 Curso Completo Full Stack com IA
├── 🔧 Módulo 1: Setup & Ferramentas
├── 🌳 Módulo 2: Git Profissional
├── 🎨 Módulo 3: Design com IA
├── 🖥️ Módulo 4: Frontend Fundamentals
├── ⚡ Módulo 5: Next.js
├── 🤖 Módulo 6: IA no Desenvolvimento
├── ☕ Módulo 7: Java Puro
├── 🍃 Módulo 8: Spring Framework
├── 🐳 Módulo 9: Docker & Infraestrutura
├── 🗄️ Módulo 10: Banco de Dados
├── 📚 Módulo 11: Documentação & Testes
└── 🔒 Módulo 12: Segurança (Spring Security)
```

---

## Módulo 1: Setup & Ferramentas
**Duração estimada**: 1-2 horas | **Aulas**: 4-6

### 1.1 Introdução ao Curso
- Apresentação do que será ensinado
- Metodologia e filosofia do curso
- IA como ferramenta de performance, não substituta
- Como aproveitar melhor o curso

### 1.2 Setup - Frontend (Thiago)
- Instalação do Node.js e npm
- Instalação do VS Code
- Extensões essenciais do VS Code
  - ESLint
  - Prettier
  - GitLens
  - GitHub Copilot (ou alternativas)
- Configuração do Terminal
- Teste: "Hello World" em HTML

### 1.3 Setup - Backend (Rodolfo)
- Instalação do Java
- SDK Man - Gerenciamento de versões do Java
  - Por que usar SDK Man
  - Instalação e configuração
  - Como alternar entre versões
  - Versões específicas por projeto
- IDE: IntelliJ ou VS Code para Java
- Teste: "Hello World" em Java

### 1.4 Setup - Docker (Rodolfo)
- O que é Docker e por que usar
- Instalação do Docker Desktop
- Conceitos básicos: containers, images
- Primeiro container: Hello World
- Docker CLI: comandos essenciais

### 1.5 Setup - Git e GitHub
- Instalação do Git
- Configuração inicial (user.name, user.email)
- GitHub CLI (gh)
- Autenticação SSH
- Teste: primeiro repositório

---

## Módulo 2: Git Profissional
**Duração estimada**: 3-4 horas | **Aulas**: 8-12

### 2.1 Git Fundamentals
- O que é controle de versão
- Inicializando repositório (git init)
- Staging area (git add)
- Primeiro commit (git commit)
- Histórico (git log)

### 2.2 Conventional Commits
- O que são Conventional Commits
- Estrutura: type(scope): message
- Tipos: feat, fix, chore, docs, style, refactor, test
- Exemplos práticos
- Por que usar

### 2.3 IA para Commits (Copilot)
- Configurando GitHub Copilot
- Gerando mensagens de commit automaticamente
- Analisando mudanças nos arquivos
- Commits em português vs inglês
- Boas práticas

### 2.4 Branches
- O que são branches
- Criando e alternando branches
- Estratégias de branching (Git Flow simplificado)
- Main/Master vs Development
- Feature branches

### 2.5 Merge vs Rebase
- Diferença entre merge e rebase
- Quando usar cada um
- Histórico linear vs não-linear
- Rebase interativo
- Resolução de conflitos

### 2.6 Organizando o Histórico
- Por que histórico organizado importa
- Rebase para limpar commits
- Squash de commits
- Amend de commits
- Reordenação de commits

### 2.7 Pull Requests Profissionais
- O que é uma Pull Request
- Criando PR via GitHub CLI
- Estrutura de uma boa PR
  - Título claro
  - Descrição detalhada
  - Checklist
  - Screenshots (quando aplicável)
- IA para gerar descrição de PR
- Code Review

### 2.8 Tags e Releases
- O que são tags
- Versionamento semântico (SemVer)
- Criando tags
- Releases no GitHub
- Automação com CI/CD (introdução)
- Vercel + GitHub (exemplo de deploy automático)

---

## Módulo 3: Design com IA
**Duração estimada**: 4-5 horas | **Aulas**: 10-14

### 3.1 Coleta de Requisitos
- Template de requisitos
  - Nome do projeto
  - Branding (se existir)
  - Cores principais
  - Descrição do projeto
  - Problema que resolve
  - Objetivo
  - Público-alvo
  - Mercado
- Como preencher cada campo
- Exemplos práticos

### 3.2 Pesquisa de Referências
- Onde buscar inspiração
  - Behance
  - Dribbble
  - Awwwards
  - Pinterest
- Como selecionar boas referências
- Printando e organizando referências
- Identificando padrões visuais

### 3.3 Criando Prompt para IA
- IA como assistente de design
- Estrutura de um bom prompt
- Combinando requisitos + referências
- Ferramentas: ChatGPT, Claude, Gemini
- Gerando descrição detalhada do layout
- Iteração e refinamento

### 3.4 Stitch - Gerando o Design
- O que é Stitch
- Cadastro e acesso
- Usando o prompt gerado
- Anexando prints de referência
- Gerando as primeiras telas
- Avaliando o resultado

### 3.5 Download e Conversão
- Exportando do Stitch
- Formatos disponíveis
- Convertendo para Figma
- Importando no Figma

### 3.6 Figma Básico - Parte 1
- Interface do Figma
- Navegação e zoom
- Selecionando elementos
- Movendo e redimensionando
- Camadas (layers)

### 3.7 Figma Básico - Parte 2
- Editando textos
- Alterando cores
- Espaçamentos e alinhamento
- Duplicando elementos
- Grupos e frames

### 3.8 Padronização no Figma
- Identificando inconsistências do Stitch
  - Cores variando (diferentes tons de verde)
  - Espaçamentos irregulares
  - Tamanhos de fonte inconsistentes
- Criando paleta de cores unificada
- Definindo scale de espaçamentos
- Tipografia consistente

### 3.9 Plugin Code Tia
- O que é o plugin
- Instalação
- Convertendo HTML para Figma
- Casos de uso
- Editando após conversão

### 3.10 Finalizando o Layout
- Última revisão
- Checklist de qualidade
- Exportando assets (se necessário)
- Preparando para desenvolvimento
- Handoff para dev

---

## Módulo 4: Frontend Fundamentals
**Duração estimada**: 6-8 horas | **Aulas**: 15-20

### 4.1 HTML - Estrutura
- O que é HTML
- Tags básicas (html, head, body)
- Headings (h1-h6)
- Parágrafos (p)
- Links (a)
- Listas (ul, ol, li)

### 4.2 HTML - Semântica
- Por que semântica importa
- header, nav, main, section, article, aside, footer
- Acessibilidade
- SEO

### 4.3 HTML - Formulários
- input, textarea, select
- Tipos de input
- Labels e validação
- button vs input type="submit"

### 4.4 CSS - Fundamentos
- O que é CSS
- Sintaxe: seletor { propriedade: valor; }
- Três formas de incluir CSS
- Seletores básicos

### 4.5 CSS - Box Model
- Content, padding, border, margin
- Width e height
- Box-sizing

### 4.6 CSS - Layout
- Display (block, inline, inline-block)
- Flexbox
- Grid (introdução)
- Position (static, relative, absolute, fixed)

### 4.7 CSS - Responsividade
- Media queries
- Mobile-first approach
- Breakpoints comuns
- Unidades relativas (rem, em, %, vw, vh)

### 4.8 CSS - Estilização Avançada
- Pseudo-classes (:hover, :focus, :active)
- Pseudo-elementos (::before, ::after)
- Transições
- Animações básicas

### 4.9 JavaScript - Fundamentos
- O que é JavaScript
- Variáveis (let, const, var)
- Tipos de dados
- Operadores
- Estruturas condicionais (if, else, switch)
- Loops (for, while, forEach)

### 4.10 JavaScript - Funções
- Declaração de funções
- Arrow functions
- Parâmetros e retorno
- Escopo
- Callbacks

### 4.11 JavaScript - DOM
- O que é o DOM
- querySelector e querySelectorAll
- getElementById, getElementsByClassName
- Manipulando elementos
- Criando elementos

### 4.12 JavaScript - Eventos
- addEventListener
- Eventos comuns (click, submit, change, keyup)
- Event object
- preventDefault

### 4.13 JavaScript - Async
- O que é assíncrono
- Promises
- async/await
- fetch API
- Consumindo APIs

### 4.14 JavaScript - ES6+
- Destructuring
- Spread operator
- Template literals
- Array methods (map, filter, reduce)
- Módulos (import/export)

---

## Módulo 5: Next.js
**Duração estimada**: 8-10 horas | **Aulas**: 20-25

### 5.1 Introdução ao Next.js
- O que é Next.js
- Por que usar Next.js
- Next.js vs Create React App
- Vantagens: SSR, SSG, File-based routing, API Routes

### 5.2 Diferenciando: JS, React e Next
- O que é JavaScript puro (já vimos)
- O que é React (biblioteca de UI)
  - JSX (JavaScript + XML)
  - Componentes
  - Props
  - State
- O que é Next.js (framework React)
  - Roteamento
  - Otimizações
  - Server Components

### 5.3 Criando Projeto Next.js
- create-next-app
- Estrutura de pastas
- Arquivos principais
- Rodando o servidor de desenvolvimento

### 5.4 Roteamento no Next.js
- File-based routing
- Páginas e rotas
- Dynamic routes
- Nested routes
- Route groups

### 5.5 Componentes React
- O que são componentes
- Componentes funcionais
- JSX: regras e sintaxe
- Props: passando dados
- Children

### 5.6 State e useState
- O que é state
- useState hook
- Atualizando state
- State imutável
- Múltiplos states

### 5.7 useEffect
- Ciclo de vida de componentes
- useEffect: quando executar código
- Dependency array
- Cleanup
- Casos de uso comuns

### 5.8 Arquitetura HFSA
- O que é Hybrid Feature Scoped Architecture
- Por que usar
- Estrutura de pastas
  - /app
  - /features
  - /shared
  - /components
  - /hooks
  - /utils
- Organização por feature

### 5.9 Componentes Separados
- Quando criar um componente
- Componentes pequenos e focados
- Reutilização
- Props drilling e como evitar

### 5.10 Hooks Personalizados
- O que são custom hooks
- Quando criar
- Exemplos práticos
  - useLocalStorage
  - useFetch
  - useDebounce
- Regras dos hooks

### 5.11 Estilização no Next
- CSS Modules
- Tailwind CSS (opcional)
- Styled Components
- Global CSS
- CSS-in-JS

### 5.12 Imagens e Assets
- next/image
- Otimização automática
- Layouts responsivos
- Lazy loading

### 5.13 Fonts e Metadata
- next/font
- Google Fonts
- Metadata API
- SEO

### 5.14 Navegação
- next/link
- useRouter
- Programmatic navigation
- Prefetching

### 5.15 API Routes (Introdução)
- O que são API Routes
- Criando endpoints
- Request e Response
- Quando usar

### 5.16 Fetching de Dados
- Server Components vs Client Components
- fetch no Next.js
- Caching
- Revalidação

### 5.17 Loading e Error States
- loading.js
- error.js
- Suspense boundaries
- Error boundaries

### 5.18 Forms no Next
- Forms controlados
- Validação
- Server Actions (introdução)
- Feedback ao usuário

### 5.19 Deploy
- Vercel
- Conectando com GitHub
- Deploy automático
- Environment variables
- Preview deployments

---

## Módulo 6: IA no Desenvolvimento
**Duração estimada**: 5-6 horas | **Aulas**: 12-16

### 6.1 Filosofia: IA como Ferramenta
- IA não substitui desenvolvedor
- IA aumenta performance
- Desenvolvedor deve saber revisar código
- Qualidade depende dos padrões mostrados

### 6.2 Prompt Plate vs Boilerplate
- Conceito de Prompt Plate
- Vantagens sobre boilerplate estático
- Quando usar cada abordagem

### 6.3 Documentação em Markdown
- Por que markdown
- Estrutura de documentos
- Arquivos essenciais:
  - Business Plan
  - Technical Kanban
  - Arquitetura
  - Boas Práticas
  - User Stories Flow

### 6.4 Criando Documentos de Arquitetura
- Documentando padrões de código
- Estrutura de pastas
- Convenções de nomenclatura
- Exemplos e templates

### 6.5 Criando Documentos de Boas Práticas
- Formulários
- Variáveis
- Funções
- Componentes
- APIs
- Cada área do código

### 6.6 Business Plan com IA
- Template de Business Plan
- Usando IA para gerar
- Refinando e validando
- Regras de negócio documentadas

### 6.7 Technical Kanban em MD
- Kanban dentro do VS Code
- Estrutura:
  - Épicos
  - User Stories
  - Tasks
  - Status (todo, in progress, done)
- Separando por arquivos (home-kanban.md, setup-kanban.md)

### 6.8 User Stories com IA
- O que são User Stories
- Formato: "Como [persona], quero [ação], para [benefício]"
- Critérios de aceite
- Usando IA para quebrar features em User Stories

### 6.9 Ferramentas de IA
- GitHub Copilot
- ChatGPT Codex
- Claude (Anthropic)
- Gemini
- Cursor (pros e contras)
- Comparação e quando usar cada uma

### 6.10 Workflow com IA
- Selecionando código e contexto
- Executando User Story
- IA executa: lint, build, test, update docs
- Atualiza kanban automaticamente
- Gerando descrição de PR

### 6.11 Configurando a IA (cloud.md)
- Arquivo cloud.md
- Instruções para a IA
- Steps to User Story
- Workflow definido
- Padrões de código

### 6.12 Design Tokens com IA
- Documentando design tokens
- Cores, tipografia, espaçamentos
- IA mantém consistência

### 6.13 Feedback por Voz + IA
- Ferramenta de transcrição
- Descrevendo problemas enquanto testa
- Transcrição → Prompt para IA
- IA sugere solução técnica

### 6.14 Revisão de Código
- IA não é infalível
- Desenvolvedor deve revisar
- Checklist de revisão
- Corrigindo código gerado

### 6.15 TDD com IA (Introdução)
- Conceito de TDD
- IA criando testes primeiro
- Código para passar nos testes
- Ciclo Red-Green-Refactor

---

## Módulo 7: Java Puro
**Duração estimada**: 6-8 horas | **Aulas**: 15-20

### 7.1 Por que Java Puro Primeiro
- Entender o legado
- Fundamentos antes de frameworks
- Diferenciar Java de Spring

### 7.2 Sintaxe Básica
- Estrutura de um programa Java
- public static void main
- System.out.println
- Comentários

### 7.3 Variáveis e Tipos
- Tipos primitivos (int, double, boolean, char)
- String
- Declaração e inicialização
- Constantes (final)

### 7.4 Operadores
- Aritméticos
- Relacionais
- Lógicos
- Atribuição

### 7.5 Estruturas Condicionais
- if, else if, else
- switch
- Operador ternário

### 7.6 Loops
- for
- while
- do-while
- foreach
- break e continue

### 7.7 Arrays
- Declaração e inicialização
- Acessando elementos
- Iterando
- Arrays multidimensionais

### 7.8 Métodos
- Declaração
- Parâmetros
- Retorno
- Sobrecarga (overload)

### 7.9 Orientação a Objetos - Classes
- O que é uma classe
- Atributos
- Métodos
- Construtores
- this

### 7.10 Orientação a Objetos - Objetos
- Instanciando objetos
- new
- Acessando membros
- Modificadores de acesso (public, private, protected)

### 7.11 Encapsulamento
- Getters e Setters
- Por que encapsular
- Validação

### 7.12 Herança
- extends
- super
- Sobrescrita (override)
- Polimorfismo

### 7.13 Interfaces
- interface
- implements
- Contratos
- Múltiplas interfaces

### 7.14 Classes Abstratas
- abstract
- Quando usar
- Diferença de interface

### 7.15 Composição
- "Has-a" vs "Is-a"
- Quando preferir composição
- Exemplos práticos

### 7.16 Exceções
- try, catch, finally
- throw e throws
- Exceções checked e unchecked
- Criando exceções personalizadas

### 7.17 Collections
- List (ArrayList, LinkedList)
- Set (HashSet, TreeSet)
- Map (HashMap, TreeMap)
- Iterando sobre collections

### 7.18 API REST em Java Puro
- O que é REST
- Criando servidor HTTP básico (HttpServer)
- Endpoints
- Métodos HTTP (GET, POST, PUT, DELETE)
- JSON (usando biblioteca básica)

### 7.19 CRUD Básico em Java Puro
- Create (POST)
- Read (GET)
- Update (PUT)
- Delete (DELETE)
- Em memória (sem banco por enquanto)

---

## Módulo 8: Spring Framework
**Duração estimada**: 8-10 horas | **Aulas**: 20-25

### 8.1 O que é Spring
- Ecossistema Spring
- Spring Boot
- Por que Spring facilita
- Diferença: Java vs Spring

### 8.2 Criando Projeto Spring Boot
- Spring Initializr
- Dependências essenciais
- Estrutura de pastas
- application.properties

### 8.3 Anotações Spring
- @SpringBootApplication
- @RestController
- @RequestMapping
- @GetMapping, @PostMapping, etc.
- O que é Java e o que é Spring (diferenciando)

### 8.4 Primeiro Endpoint
- Criando controller
- Retornando String
- Retornando JSON
- PathVariable e RequestParam

### 8.5 Injeção de Dependência
- O que é DI
- @Service
- @Repository (introdução)
- @Autowired
- Benefícios

### 8.6 Modelo de Dados
- @Entity (introdução)
- Classes de modelo (DTOs)
- Records (Java 14+)

### 8.7 Service Layer
- Separação de responsabilidades
- Controller → Service → Repository
- Regras de negócio no Service

### 8.8 Request e Response
- @RequestBody
- @ResponseBody
- @ResponseEntity
- Status HTTP

### 8.9 Validação
- @Valid
- @NotNull, @NotBlank, @Email
- BindingResult
- Tratamento de erros de validação

### 8.10 Exception Handling
- @ControllerAdvice
- @ExceptionHandler
- Respostas padronizadas de erro
- Códigos HTTP apropriados

### 8.11 CORS
- O que é CORS
- Por que é necessário
- Configurando CORS no Spring
- @CrossOrigin

---

## Módulo 9: Docker & Infraestrutura
**Duração estimada**: 6-8 horas | **Aulas**: 15-18

### 9.1 Docker - Conceitos Avançados
- Images vs Containers
- Dockerfile
- .dockerignore
- Layers e cache

### 9.2 Criando Dockerfile para Java
- FROM
- WORKDIR
- COPY
- RUN
- CMD vs ENTRYPOINT
- Multi-stage builds

### 9.3 Docker Compose
- O que é docker-compose
- docker-compose.yml
- Serviços
- Networks
- Volumes

### 9.4 Volumes Docker
- Por que usar volumes
- Tipos de volumes
- Bind mounts
- Persistência de dados

### 9.5 Docker Networks
- Comunicação entre containers
- Bridge network
- Host network
- Container name resolution

### 9.6 Subindo Aplicação no Docker
- Build da aplicação
- Criando imagem
- Rodando container
- Mapeamento de portas

### 9.7 Estatísticas e Monitoramento
- docker stats
- Recursos (CPU, memória)
- Logs (docker logs)
- Troubleshooting

### 9.8 Docker Swarm
- O que é orquestração
- Inicializando Swarm
- Services vs Containers
- Réplicas

### 9.9 Gerenciamento de Réplicas
- Escalando aplicação
- Configurando memória
- Configurando CPU
- Load balancing

### 9.10 Proxy Reverso - Nginx
- O que é proxy reverso
- Por que usar Nginx
- Instalação via Docker
- Configuração básica
- Redirecionamento de tráfego

### 9.11 Nginx - Configuração Avançada
- SSL (introdução)
- Gzip
- Caching
- Rate limiting

---

## Módulo 10: Banco de Dados
**Duração estimada**: 4-5 horas | **Aulas**: 10-12

### 10.1 Banco de Dados - Fundamentos
- Relacional vs NoSQL (introdução)
- Escolhendo banco (PostgreSQL)
- Por que usar banco de dados

### 10.2 PostgreSQL via Docker
- docker-compose com Postgres
- Variáveis de ambiente
- Volumes para persistência
- pgAdmin (opcional)

### 10.3 SQL Básico
- CREATE TABLE
- INSERT
- SELECT
- UPDATE
- DELETE
- WHERE, ORDER BY, LIMIT

### 10.4 Spring Data JPA
- O que é JPA
- @Entity, @Id, @GeneratedValue
- @Table
- Tipos de dados

### 10.5 Repository
- JpaRepository
- Métodos prontos (findAll, findById, save, delete)
- Query methods
- @Query

### 10.6 Conectando Spring ao Banco
- application.properties
  - URL de conexão
  - Username e password
  - Dialect
  - DDL-auto
- Testando conexão

### 10.7 CRUD com Banco Real
- Refatorando para usar banco
- Create
- Read
- Update
- Delete
- Tratamento de erros (ex: registro não encontrado)

### 10.8 Relacionamentos
- @OneToMany
- @ManyToOne
- @ManyToMany
- Cascade
- Fetch types (Lazy vs Eager)

### 10.9 Migrations (Flyway - Opcional)
- O que são migrations
- Versionamento de schema
- Flyway básico

---

## Módulo 11: Documentação & Testes
**Duração estimada**: 5-6 horas | **Aulas**: 12-15

### 11.1 Postman
- O que é Postman
- Instalação
- Criando requisições
- Collections
- Environments
- Testes básicos

### 11.2 OpenAPI (Swagger)
- O que é OpenAPI
- Por que documentar APIs
- Swagger UI

### 11.3 Swagger no Spring
- Dependência Springdoc
- Acessando Swagger UI
- Annotations (@Operation, @ApiResponse)
- Customizando

### 11.4 IA para Gerar Swagger
- Gerando YAML com IA
- Template do Swagger
- IA explica configurações
- Por que automatizar

### 11.5 Introdução a Testes
- Por que testar
- Tipos de testes (unitário, integração, e2e)
- Pirâmide de testes

### 11.6 JUnit
- Setup de testes
- @Test
- Assertions
- @BeforeEach, @AfterEach

### 11.7 Testando Services
- Mockito
- @Mock, @InjectMocks
- Testando lógica de negócio

### 11.8 Testando Controllers
- MockMvc
- Testando endpoints
- Verificando status e responses

### 11.9 TDD com IA - Conceito
- Red-Green-Refactor
- IA criando testes primeiro
- Desenvolvendo código para passar nos testes

### 11.10 TDD com IA - Prática
- Exemplo completo
- User Story → Testes → Código
- Benefícios da abordagem

### 11.11 Integração de Testes no Workflow
- Rodando testes antes de commit
- CI/CD (introdução)
- IA executando testes automaticamente

---

## Módulo 12: Segurança (Spring Security)
**Duração estimada**: 6-8 horas | **Aulas**: 15-18

### 12.1 Por que Segurança Importa
- Riscos de aplicações sem segurança
- OWASP Top 10 (introdução)
- Autenticação vs Autorização

### 12.2 Spring Security - Introdução
- O que é Spring Security
- Dependência
- Segurança nativa automática

### 12.3 Configuração Básica
- SecurityFilterChain
- Desabilitando segurança para testar
- Habilitando para endpoints específicos

### 12.4 Modelo de Usuário
- Entidade User
- Roles e Authorities
- Senha criptografada (BCrypt)

### 12.5 Cadastro de Usuário
- Endpoint de registro
- Validação de dados
- Salvando com senha criptografada
- Evitando duplicação (email único)

### 12.6 Autenticação
- Endpoint de login
- Verificando credenciais
- UserDetailsService
- AuthenticationManager

### 12.7 JWT - Conceitos
- O que é JWT
- Estrutura (Header, Payload, Signature)
- Por que usar
- Stateless authentication

### 12.8 JWT - Implementação
- Dependência (jjwt)
- Gerando token
- Validando token
- Configurando expiração

### 12.9 Filtros de Segurança
- OncePerRequestFilter
- Verificando token em cada requisição
- Extraindo usuário do token
- SecurityContextHolder

### 12.10 Protegendo Endpoints
- Configurando quais endpoints são públicos
- Quais exigem autenticação
- antMatchers / requestMatchers

### 12.11 Autorização - Roles
- Atribuindo roles aos usuários
- @PreAuthorize
- Verificando permissões
- ADMIN vs USER (exemplo)

### 12.12 CRUD com Autorização
- Create: apenas autenticado
- Read: autenticado
- Update: apenas dono do recurso ou ADMIN
- Delete: apenas ADMIN

### 12.13 Tratamento de Erros de Segurança
- 401 Unauthorized
- 403 Forbidden
- Mensagens claras
- AuthenticationEntryPoint

### 12.14 Refresh Token (Opcional Avançado)
- Conceito
- Implementação básica
- Segurança adicional

### 12.15 Projeto Final Integrado
- API completa com autenticação
- CRUD protegido
- Diferentes níveis de acesso
- Documentação no Swagger
- Testes

---

## Projeto Integrador Final
**Duração estimada**: 4-6 horas | **Aulas**: 3-5

### Aplicação Completa
- **Frontend**: Next.js com design criado no Stitch/Figma
- **Backend**: Spring Boot com Java
- **Autenticação**: JWT
- **Banco**: PostgreSQL
- **Deploy**: Vercel (front) + Docker (back)
- **IA**: Fluxo completo de desenvolvimento

### Exemplo Sugerido: Sistema de Gerenciamento de Imóveis
- Usuário se cadastra e faz login
- CRUD de imóveis (apenas donos editam/deletam seus imóveis)
- Admin pode gerenciar tudo
- Design moderno com IA
- Documentação automática
- Testes

---

## Aulas Bônus / Complementares (Futuras)

### Padrões de Projeto
- Singleton
- Factory
- Strategy
- Observer

### BDD (Behavior-Driven Development)
- Cucumber
- Gherkin

### Testes E2E
- Selenium
- Cypress

### CI/CD
- GitHub Actions
- Pipelines automatizados

### Outras Features
- Paginação
- Filtros e busca
- Upload de arquivos
- Emails
- Notificações

---

## Notas Importantes

> **Cada aula deve**:
> - Ter script preparado
> - Ser gravada com pausas silenciosas em erros (técnica de edição)
> - Incluir exemplos práticos
> - Terminar com recap

> **Ordem é importante**: Fundamentos antes de frameworks, Java antes de Spring, Design antes de Dev.

> **IA é transversal**: aparece em Git, Design, Desenvolvimento e Testes.

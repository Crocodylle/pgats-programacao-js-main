# PGATS - Programação JavaScript

Um curso completo de programação JavaScript com foco em conceitos fundamentais e exercícios práticos.

## 📋 Sobre o Projeto

Este repositório contém o material didático do curso PGATS (Pós-Graduação em Automação de Testes de Software) - módulo de Programação JavaScript. O curso utiliza exemplos práticos relacionados a um abrigo de cães para tornar o aprendizado mais engajante e contextualizado.

## 🚀 Configuração do Projeto

### Tecnologias Utilizadas
- **JavaScript (ES6+)** com módulos ES
- **Node.js** como runtime
- **Mocha** para testes unitários
- **GitHub Actions** para CI/CD

### Instalação
```bash
# Clone o repositório
git clone [repository-url]

# Instale as dependências
yarn install
# ou
npm install

# Execute os testes
yarn test
# ou
npm test
```

## 📁 Estrutura do Projeto

### 📚 Conceitos (`/conceitos`)
Arquivos que demonstram conceitos fundamentais da linguagem JavaScript:

- **async-await.js** - Programação assíncrona
- **condicionais-if-else.js** - Estruturas condicionais básicas
- **condicionais-switch-case.js** - Estruturas de seleção múltipla
- **excecoes.js** - Tratamento de erros e exceções
- **funcoes-de-seta.js** - Arrow functions e suas características
- **funcoes-tradicionais.js** - Funções declaradas e expressões de função
- **modularizacao-export.js** - Exportação de módulos ES6
- **modularizacao-import.js** - Importação de módulos ES6
- **operadores-adicionais.js** - Operadores especiais do JavaScript
- **operadores-aritmeticos.js** - Operações matemáticas básicas
- **operadores-comparacao.js** - Operadores de comparação e igualdade
- **operadores-logicos.js** - Operadores lógicos (&&, ||, !)
- **repeticao-for.js** - Estruturas de repetição com for
- **repeticao-forEach.js** - Método forEach para arrays
- **repeticao-while.js** - Estruturas de repetição com while
- **testes-de-unidade.js** - Introdução aos testes unitários

### 🎯 Exercícios (`/exercicios`)
Exercícios práticos para aplicação dos conceitos aprendidos:

- **03-exercicio.js** até **09-exercicio.js** - Exercícios progressivos
- **10-exercicio-dados.js** - Estruturas de dados
- **10-exercicio-funcao.js** - Implementação de funções
- **10-exercicio-principal.js** - Arquivo principal do exercício modular

### 📖 Arquivos Principais
- **index.js** - Arquivo principal com demonstrações de:
  - Console API (log, error, warn, table)
  - Constantes e variáveis
  - Tipos de dados JavaScript
  - Manipulação de strings
  - Template literals
  - Métodos de string (split, toLowerCase, toUpperCase, includes, etc.)

- **01-exercicio.js** - Gerador de tags de identificação para cães
- **02-exercicio.js** - Continuação dos exercícios básicos
- **trabalho.js** - Projeto final: gerador de tags de identificação

### 🧪 Testes (`/testes`)
Implementação de testes unitários seguindo práticas de TDD:

- **01-testes.js** - Suite de testes principal com:
  - Testes para formatação de nomes
  - Exemplos de assertions
  - Estrutura de testes com describe/it

### 📁 GitHub (`.github`)
Configuração de automação e CI/CD:

- **workflows/manual-exec.yaml** - Pipeline de CI que:
  - Executa manualmente via GitHub Actions
  - Instala dependências com Yarn
  - Executa testes unitários
  - Roda em ambiente Ubuntu

## 🎓 Conceitos Abordados

### Fundamentos
- Variáveis e constantes (`const`, `let`, `var`)
- Tipos de dados (String, Number, Boolean, Array, Object)
- Hoisting (içamento de variáveis)
- Template literals e interpolação

### Estruturas de Controle
- Condicionais (`if/else`, `switch/case`)
- Loops (`for`, `while`, `forEach`)
- Operadores (aritméticos, comparação, lógicos)

### Funções
- Funções tradicionais vs arrow functions
- Parâmetros e valores padrão
- Retorno de valores
- Escopo de variáveis

### Programação Avançada
- Modularização (import/export)
- Tratamento de exceções (try/catch)
- Programação assíncrona (async/await)
- Testes unitários com assertions

### Manipulação de Dados
- Métodos de string
- Manipulação de arrays
- Objetos e suas propriedades
- Destructuring e spread operator

## 🏃‍♂️ Como Executar

### Executar Arquivo Individual
```bash
node conceitos/funcoes-tradicionais.js
node exercicios/03-exercicio.js
```

### Executar Arquivo Principal
```bash
node index.js
```

### Executar Testes
```bash
yarn test
```

### Executar via GitHub Actions
1. Acesse a aba "Actions" no GitHub
2. Selecione "Execução Manual"
3. Clique em "Run workflow"
4. Insira um nome para o pipeline
5. Execute

## 📈 Metodologia de Ensino

O curso segue uma abordagem prática e progressiva:

1. **Conceitos Teóricos** - Explicação dos fundamentos
2. **Exemplos Práticos** - Demonstrações com código real
3. **Exercícios Aplicados** - Problemas para resolver
4. **Testes Unitários** - Validação das implementações
5. **TDD** - Test Driven Development como boa prática

## 🐕 Temática do Curso

Os exemplos utilizam um contexto de **abrigo de cães** para tornar o aprendizado mais envolvente, incluindo:
- Cadastro de informações de cães
- Geração de tags de identificação
- Controle de adoções
- Manipulação de dados dos animais

## 🛠️ Ferramentas de Desenvolvimento

- **ES Modules** - Sistema de módulos moderno
- **Mocha** - Framework de testes
- **Node.js** - Runtime JavaScript
- **Yarn** - Gerenciador de pacotes
- **GitHub Actions** - Integração contínua

## 📝 Estrutura de Commits

O projeto mantém um histórico limpo com commits organizados que demonstram a evolução do aprendizado através dos diferentes conceitos e exercícios implementados.

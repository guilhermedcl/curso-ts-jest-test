# 🧪  Curso TypeScript com Testes (Jest)

Repositório com os exercícios e exemplos práticos desenvolvidos durante o módulo de testes do curso [JavaScript e TypeScript do básico ao avançado JS/TS (Udemy)](https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado).

---

## 🧠 Conteúdo abordado no repositório

- Testes unitários com Jest
- Cobertura de testes
- Tipagem com interfaces e protocolos no TypeScript
- Mocks e fakes para simulação de dependências
- Estruturação de classes com responsabilidade única 
- Separação entre camadas 
- Testes de asserções específicas

---

## 📁 Estrutura do projeto

- `coverage/`: pasta que será gerada automaticamente ao rodar o comando `npm run`, com os relatórios de cobertura de testes.
- `src/`: código-fonte e testes divididos por contexto:
- `classes/`: implementação principal das funcionalidades.
- `interfaces/`: contratos utilizados entre componentes (ex:mensagens, carrinho, etc).
- `examples/`: exemplos de uso e testes personalizados.
- `services/`: camadas de serviço com lógica de negócios.
- `main.ts`: ponto de entrada do sistema.
- `.vscode`, `.eslintrc.js`, `.editorconfig`, `.gitignore`, `tsconfig.json`, etc.: arquivos de configuração.

---

## ⚙️ Tecnologias utilizadas

- TypeScript
- Jest (Framework de testes)
- ESLint
- Node.js (para rodar scripts npm)

---

## 🧪 Como executar os testes

1. Instale as dependências com:

```bash
npm install
```

2. Execute os testes com um dos comandos abaixo:

```bash
npm run test:silent
```
- Executa todos os testes continuamente (`--watchAll`)
- Oculta logs de console (`--silent`)
- Remove rastros de erro detalhados (`--noStackTrace`)
##
```bash
npm run test:coverage
```
- Gera o relatório de cobertura na pasta `coverage/`
- Inclui visualização em HTML (`lcov-report/`)
- Também gera arquivos `coverage-final.json` e `clover.xml`


---

## 📌 Observações

- Este repositório é voltado para praticar testes com TypeScript, dentro do contexto do curso.
- A organização em interfaces, classes e serviços segue princípios de boas práticas e TDD.

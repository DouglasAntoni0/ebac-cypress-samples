# EBAC Cypress Samples

![Cypress](https://img.shields.io/badge/Cypress-samples-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-testes-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![E2E](https://img.shields.io/badge/E2E-pratica-0A66C2?style=for-the-badge)
![QA](https://img.shields.io/badge/QA-fundamentos-2E7D32?style=for-the-badge)

Repositório de estudos com exemplos Cypress, organizado para praticar comandos, fixtures, suporte e cenários de automação end-to-end.

Este projeto funciona como base de aprendizado do framework. Ele não tenta ser uma suíte corporativa completa; seu valor está em mostrar familiaridade com a anatomia do Cypress, seus diretórios principais e o ciclo de execução de testes.

## Objetivo do projeto

O objetivo é praticar a estrutura padrão de um projeto Cypress e entender como os principais blocos se relacionam:

- specs de teste;
- fixtures;
- comandos de suporte;
- configuração do Cypress;
- execução headless;
- execução interativa.

Essa base é necessária antes de evoluir para projetos com arquitetura mais robusta, relatórios, dados dinâmicos, CI/CD e padrões de manutenção.

## O que este projeto demonstra

| Área | Evidência no projeto | Valor técnico |
| --- | --- | --- |
| Cypress básico | Estrutura padrão com `cypress/e2e`, `fixtures` e `support` | Mostra domínio da organização do framework |
| Testes exploratórios guiados | Exemplos de comandos e padrões do Cypress | Ajuda a entender possibilidades da ferramenta |
| Execução automatizada | Script `npm test` preparado para rodar `npx cypress run` | Permite repetição local |
| Base de aprendizado | Exercícios que sustentam projetos Cypress mais completos | Cria fundação para evolução técnica |
| Organização | Configuração e dependências versionadas | Facilita instalação e execução |

## Estrutura

```text
.
├── cypress/
│   ├── e2e/
│   │   ├── 1-getting-started/
│   │   └── 2-advanced-examples/
│   ├── fixtures/
│   └── support/
├── cypress.config.js
├── package.json
├── package-lock.json
└── README.md
```

## Papel dos diretórios Cypress

| Diretório | Finalidade |
| --- | --- |
| `cypress/e2e` | Onde ficam os arquivos de teste |
| `cypress/fixtures` | Massa de dados estática para testes |
| `cypress/support` | Comandos customizados e configuração global |
| `cypress.config.js` | Configuração principal do Cypress |

## Como executar

Clone o projeto:

```bash
git clone https://github.com/DouglasAntoni0/ebac-cypress-samples.git
cd ebac-cypress-samples
```

Instale dependências:

```bash
npm install
```

Execute a suíte:

```bash
npm test
```

Para abrir a interface do Cypress:

```bash
npx cypress open
```

## Como estudar este repositório

Uma forma eficiente de usar este projeto como estudo:

1. Abra a estrutura de pastas.
2. Leia os exemplos em `cypress/e2e`.
3. Execute os testes no modo interativo.
4. Observe o comportamento no Test Runner.
5. Altere pequenos trechos para entender como o Cypress reage.
6. Rode novamente em modo headless.

## Estratégia de aprendizado

Este repositório cobre a fase de familiarização com a ferramenta. Ele ajuda a responder perguntas como:

- onde ficam os testes?
- onde ficam massas de dados?
- onde posso criar comandos reutilizáveis?
- como rodo a suíte no terminal?
- como abro a execução visual?
- como o Cypress organiza seus exemplos?

## Resultado técnico

O repositório mostra familiaridade com a anatomia do Cypress e seus recursos de apoio. Essa base é importante porque bons projetos de QA começam com domínio do framework antes de avançar para arquitetura, relatórios, CI/CD e padrões de manutenção.

## Competências evidenciadas

- Estrutura de projeto Cypress.
- Execução local de testes.
- Uso de `fixtures` e `support`.
- Noção de specs E2E.
- Leitura de exemplos avançados.
- Organização de dependências com npm.

## Possíveis evoluções

- Criar specs próprias com aplicação alvo real.
- Adicionar Page Objects ou App Actions.
- Criar custom commands.
- Integrar Mochawesome para relatórios.
- Adicionar GitHub Actions.
- Separar suites por smoke e regressão.

## Conclusão

Este repositório cumpre um papel de fundação. Ele mostra o contato com a estrutura do Cypress, prepara o terreno para automações mais robustas e demonstra uma progressão natural de aprendizado em QA Automation.

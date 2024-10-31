
# Commit Semântico - Tipos e Exemplos

## 1. `feat`: Adicionando um novo recurso
Este tipo é usado quando se cria uma nova funcionalidade no sistema.

Exemplo:
```
feat: add user authentication flow
```

## 2. `fix`: Correção de bugs
Utilizado para correções de defeitos no código que afetam o comportamento do sistema.

Exemplo:
```
fix: resolve login redirect issue
```

## 3. `docs`: Alterações na documentação
Usado para mudanças em arquivos de documentação, como arquivos README, guias de instalação, etc.

Exemplo:
```
docs: update API usage instructions
```

## 4. `style`: Alterações de estilo de código (espaços, vírgulas, etc) sem impactar na lógica do sistema
Este commit não altera a funcionalidade ou comportamento do código, mas foca em melhorias de formatação ou estilo.

Exemplo:
```
style: format code according to ESLint rules
```

## 5. `refactor`: Refatoração de código que não corrige bugs nem adiciona novos recursos
Usado para melhorias ou reestruturações que não alteram o comportamento do código.

Exemplo:
```
refactor: optimize user data fetching
```

## 6. `test`: Adição ou alteração de testes
Utilizado quando se adicionam ou ajustam testes de unidade, integração ou outros.

Exemplo:
```
test: add unit tests for login service
```

## 7. `chore`: Atualizações de tarefas de build ou ferramentas auxiliares
Este tipo é para commits que não modificam o código da aplicação diretamente, como atualizações de pacotes, configurações de build, etc.

Exemplo:
```
chore: update dependencies to latest versions
```

## 8. `perf`: Melhorias de performance
Usado quando se otimiza o código para melhorar o desempenho da aplicação.

Exemplo:
```
perf: improve API response time by caching
```

## 9. `ci`: Alterações no sistema de integração contínua
Para commits relacionados à configuração ou ao funcionamento de sistemas de CI (Continuous Integration).

Exemplo:
```
ci: configure CircleCI to run tests
```

## 10. `build`: Mudanças no sistema de build ou dependências externas
Utilizado para alterar processos de build, dependências, ou ferramentas que compõem o build da aplicação.

Exemplo:
```
build: add webpack for asset bundling
```

## 11. `revert`: Reverter um commit anterior
Usado quando é necessário desfazer um commit anterior.

Exemplo:
```
revert: revert commit 1234567 due to breaking change
```

## 12. `env`: Mudanças relacionadas ao ambiente da aplicação
Utilizado para modificações que afetam o ambiente de desenvolvimento ou produção.

Exemplo:
```
env: update environment variables for production
```

## 13. `hotfix`: Correção urgente de bug em produção
Quando é necessário realizar uma correção rápida de um problema crítico em produção.

Exemplo:
```
hotfix: fix payment gateway crash on checkout
```

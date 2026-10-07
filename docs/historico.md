# Ordem real de desenvolvimento

## Funcionalidade 1 — Limpar filtros

1. `4bf4d7a`: primeiro commit da funcionalidade em `feature/limpar-filtros`.
2. Interrupção: criada `bugfix/busca-urgente` a partir da master.
3. `0d82726`: correção da busca sem hífen; integrada na master.
4. Retorno à feature e incorporação da correção urgente.
5. `314c65a`: segundo commit da funcionalidade, finalizando feedback e estilo.
6. [PR #1](https://github.com/marianesilvaflores/atividade-interrupcoes/pull/1): integrado na master.

## Funcionalidade 2 — Porções rápidas

1. `e1c6881`: primeiro commit da funcionalidade em `feature/porcoes-rapidas`.
2. Interrupção: criada `bugfix/contraste-urgente` a partir da master.
3. `9a8c60c`: correção de contraste do atalho; integrada na master.
4. Retorno à feature e incorporação da correção urgente.
5. `6230fb1`: segundo commit da funcionalidade, finalizando seleção e layout.
6. [PR #2](https://github.com/marianesilvaflores/atividade-interrupcoes/pull/2): integrado na master.

Os commits de merge documentam as integrações e não contam como os dois commits de implementação de cada funcionalidade. Não houve revisão externa; execução individual declarada no README.

## Validação

Verificações realizadas no navegador:

- Buscar milkshake sem hífen encontra um produto.
- Limpar filtros restaura os três produtos e anuncia a limpeza.
- Selecionar 300 g calcula R$ 18,00; selecionar 100 g calcula R$ 6,00.
- Digitar 150 g desmarca a porção de 300 g.
- JavaScript aprovado em `node --check script.js`.

A correção de contraste define texto #321e28 sobre fundo #fff2e8 para o atalho no tema escuro.

# Doce Gelado — Funcionalidades e correções urgentes

> **Observação ao professor:** Realizei esta atividade individualmente por estar em recuperação e não ter um colega disponível, pois os demais já haviam concluído a tarefa. Para demonstrar minha compreensão dos conceitos, registrei o desenvolvimento de duas funcionalidades, a interrupção para correções urgentes em branches separadas, a retomada do desenvolvimento e a abertura dos pull requests para a `master`. Não houve participação ou revisão de outro colaborador.

Projeto acadêmico de **Mariane Silva Flores**, desenvolvido com apoio de IA, em HTML, CSS e JavaScript. Baseado no [atividade-branchs](https://github.com/marianesilvaflores/atividade-branchs). Abra `index.html` no navegador para executar.

## Simulação de atendimento urgente

As urgências são uma simulação didática. Os dois problemas já existiam na versão base; não foram introduzidos para esta atividade. As correções de busca e contraste foram reaplicadas aqui como exercício independente do repositório `atividade-bugfix`.

| Funcionalidade | Interrupção após o primeiro commit | Retomada |
| --- | --- | --- |
| Limpar filtros | Busca por milkshake sem hífen não encontra o produto | Finalizar botão acessível e seu feedback |
| Porções rápidas | Link Pular para o cardápio perde contraste no tema escuro | Finalizar seleção de porções e indicação da escolha |

Cada funcionalidade tem dois commits próprios. Entre eles, foi criada uma branch `bugfix/...` a partir da `master`, corrigido o problema e integrado o bugfix na principal. Em seguida, a branch da funcionalidade recebeu a correção e seu desenvolvimento foi retomado. Os merges preservam o histórico; os commits não foram agrupados ou reordenados.

## Como conferir

Consulte o histórico com `git log --graph --oneline --all`. O arquivo `docs/historico.md` registra os commits na ordem real de execução. Os pull requests das funcionalidades apontam para `master`.

## Créditos

Imagens geradas com IA da OpenAI para a sorveteria original. Fontes DM Sans e Fraunces via Google Fonts. Preços ilustrativos; o site não envia pedidos nem processa pagamentos.

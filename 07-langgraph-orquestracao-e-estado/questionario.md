# Questionário — LangGraph: estado e orquestração

Responda sem consultar o gabarito. Cada etapa tem duas questões; conclua a etapa após explicar ambas. Critério do módulo: 5 de 6 acertos, prática pronta e correção dos erros.

## Após a etapa 1

1. O que é estado no grafo?

2. Para que serve aresta condicional?


## Após a etapa 2

3. O que o checkpoint guarda?

4. Por que idempotência?


## Após a etapa 3

5. Onde colocar revisão humana?

6. Quando LangGraph é útil?


<details><summary>Gabarito comentado — abra depois de responder</summary>

1. **O que é estado no grafo?** Dados compartilhados atualizados pelos nós da execução.

2. **Para que serve aresta condicional?** Escolher o próximo nó segundo uma condição explícita.

3. **O que o checkpoint guarda?** Estado para retomar execução em uma thread.

4. **Por que idempotência?** Para evitar duplicar efeitos quando uma etapa é repetida.

5. **Onde colocar revisão humana?** Antes de ações com impacto ou baixa confiança.

6. **Quando LangGraph é útil?** Quando há rotas, estado, pausas ou retomadas além de uma cadeia simples.

</details>

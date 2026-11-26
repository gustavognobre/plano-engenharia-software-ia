# Questionário — APIs e aplicativos inteligentes

Responda sem consultar o gabarito. Cada etapa tem duas questões; conclua a etapa após explicar ambas. Critério do módulo: 5 de 6 acertos, prática pronta e correção dos erros.

## Após a etapa 1

1. Por que separar adaptador do provedor?

2. O que fazer com timeout?


## Após a etapa 2

3. Onde guardar a API key?

4. Qual vantagem do mock?


## Após a etapa 3

5. Por que validar a saída?

6. O que registrar em produção?


<details><summary>Gabarito comentado — abra depois de responder</summary>

1. **Por que separar adaptador do provedor?** Para trocar modelo sem alterar a lógica do produto.

2. **O que fazer com timeout?** Tratar a falha, aplicar retry limitado quando seguro e informar o usuário.

3. **Onde guardar a API key?** Em variável de ambiente ou gerenciador de segredos.

4. **Qual vantagem do mock?** Testar fluxo sem chamada paga ou rede.

5. **Por que validar a saída?** O modelo pode descumprir o formato solicitado.

6. **O que registrar em produção?** Evento, duração, erro e uso, sem vazar dados sensíveis.

</details>

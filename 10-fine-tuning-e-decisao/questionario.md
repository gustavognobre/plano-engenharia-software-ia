# Questionário — Fine tuning: quando fazer

Responda sem consultar o gabarito. Cada etapa tem duas questões; conclua a etapa após explicar ambas. Critério do módulo: 5 de 6 acertos, prática pronta e correção dos erros.

## Após a etapa 1

1. Quando RAG é primeira escolha?

2. Quando ferramentas são primeira escolha?


## Após a etapa 2

3. Quando fine tuning pode ajudar?

4. Fine tuning insere fatos atualizados de forma confiável?


## Após a etapa 3

5. Por que separar teste por origem?

6. Qual decisão vem antes do treino?


<details><summary>Gabarito comentado — abra depois de responder</summary>

1. **Quando RAG é primeira escolha?** Quando a resposta depende de fatos/documentos atualizados e rastreáveis.

2. **Quando ferramentas são primeira escolha?** Quando o sistema precisa consultar ou alterar estado externo.

3. **Quando fine tuning pode ajudar?** Quando exemplos de qualidade ensinam comportamento repetível que prompts não estabilizaram.

4. **Fine tuning insere fatos atualizados de forma confiável?** Não; dados mudam e o modelo não garante citação ou atualização.

5. **Por que separar teste por origem?** Para reduzir vazamento de exemplos muito parecidos.

6. **Qual decisão vem antes do treino?** Comparar com baseline e definir métrica e ganho esperado.

</details>

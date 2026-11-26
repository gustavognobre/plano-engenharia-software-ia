# Questionário — RAG: busca, recuperação e citações

Responda sem consultar o gabarito. Cada etapa tem duas questões; conclua a etapa após explicar ambas. Critério do módulo: 5 de 6 acertos, prática pronta e correção dos erros.

## Após a etapa 1

1. O que o RAG altera?

2. Por que metadados?


## Após a etapa 2

3. O que mede recall@k?

4. Quando começar por busca lexical?


## Após a etapa 3

5. O que fazer sem trecho confiável?

6. Qual diferença entre falha de busca e falha de resposta?


<details><summary>Gabarito comentado — abra depois de responder</summary>

1. **O que o RAG altera?** O contexto apresentado ao modelo na inferência, não os pesos do modelo.

2. **Por que metadados?** Para filtrar, citar origem e controlar versões e acesso.

3. **O que mede recall@k?** A fração de perguntas cujo trecho relevante aparece entre os k recuperados.

4. **Quando começar por busca lexical?** Quando documentos e termos exatos permitem uma base simples e barata.

5. **O que fazer sem trecho confiável?** Declarar insuficiência de evidência e não inventar citação.

6. **Qual diferença entre falha de busca e falha de resposta?** A primeira não encontra evidência; a segunda usa mal a evidência encontrada.

</details>

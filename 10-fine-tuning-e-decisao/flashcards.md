# Flashcards — Fine tuning: quando fazer

Cubra a resposta; revise em 1, 3, 7 e 14 dias.

| Frente | Verso |
|---|---|
| Quando RAG é primeira escolha? | Quando a resposta depende de fatos/documentos atualizados e rastreáveis. |
| Quando ferramentas são primeira escolha? | Quando o sistema precisa consultar ou alterar estado externo. |
| Quando fine tuning pode ajudar? | Quando exemplos de qualidade ensinam comportamento repetível que prompts não estabilizaram. |
| Fine tuning insere fatos atualizados de forma confiável? | Não; dados mudam e o modelo não garante citação ou atualização. |
| Por que separar teste por origem? | Para reduzir vazamento de exemplos muito parecidos. |
| Qual decisão vem antes do treino? | Comparar com baseline e definir métrica e ganho esperado. |

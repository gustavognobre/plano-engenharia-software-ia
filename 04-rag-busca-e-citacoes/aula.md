# Aula — RAG: busca, recuperação e citações

## Etapa 1 — Entender

Indexação: coletar documentos autorizados, extrair texto, dividir por sentido, guardar metadados e versões.

**Verificação rápida:** explique o conceito em duas frases e dê um exemplo do seu projeto.

## Etapa 2 — Construir

Recuperação: começar por busca lexical; comparar embeddings, busca híbrida, filtros e reranking.

**Verificação rápida:** desenhe a entrada, a transformação e a saída do exercício.

## Etapa 3 — Validar

Resposta: citar trecho e origem, admitir ausência de evidência e testar recuperação separada da geração.

**Verificação rápida:** registre um caso que funciona, um caso que falha e o que você mudaria.

## Vocabulário para explicar em voz alta

- **O que o RAG altera?** O contexto apresentado ao modelo na inferência, não os pesos do modelo.
- **Por que metadados?** Para filtrar, citar origem e controlar versões e acesso.
- **O que mede recall@k?** A fração de perguntas cujo trecho relevante aparece entre os k recuperados.

## Erro comum

Concluir a etapa apenas por ter assistido ao vídeo. A conclusão exige explicar a ideia, executar o exercício e verificar um resultado observável.

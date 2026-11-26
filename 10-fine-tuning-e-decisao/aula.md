# Aula — Fine tuning: quando fazer

## Etapa 1 — Entender

Diagnóstico: medir baseline; se falta informação atual ou privada, buscar RAG; se falta integração, ferramentas/MCP.

**Verificação rápida:** explique o conceito em duas frases e dê um exemplo do seu projeto.

## Etapa 2 — Construir

Treino: usar fine tuning supervisionado para padrões de comportamento, formato ou domínio com exemplos representativos; separar treino, validação e teste.

**Verificação rápida:** desenhe a entrada, a transformação e a saída do exercício.

## Etapa 3 — Validar

Experimento: estudar SFT com LoRA/QLoRA, licenças, custo de GPU, qualidade do dataset, overfitting e comparação com baseline.

**Verificação rápida:** registre um caso que funciona, um caso que falha e o que você mudaria.

## Vocabulário para explicar em voz alta

- **Quando RAG é primeira escolha?** Quando a resposta depende de fatos/documentos atualizados e rastreáveis.
- **Quando ferramentas são primeira escolha?** Quando o sistema precisa consultar ou alterar estado externo.
- **Quando fine tuning pode ajudar?** Quando exemplos de qualidade ensinam comportamento repetível que prompts não estabilizaram.

## Erro comum

Concluir a etapa apenas por ter assistido ao vídeo. A conclusão exige explicar a ideia, executar o exercício e verificar um resultado observável.

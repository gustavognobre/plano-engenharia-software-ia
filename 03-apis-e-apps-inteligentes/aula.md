# Aula — APIs e aplicativos inteligentes

## Etapa 1 — Entender

Integração: requisições HTTP, autenticação por variável de ambiente, timeout, retry com limites e tratamento de erro.

**Verificação rápida:** explique o conceito em duas frases e dê um exemplo do seu projeto.

## Etapa 2 — Construir

Aplicação: separar interface, serviço de modelos e lógica de negócio; validar entrada e saída.

**Verificação rápida:** desenhe a entrada, a transformação e a saída do exercício.

## Etapa 3 — Validar

Entrega: criar API FastAPI, interface simples, logs sem dados privados e orçamento de tokens.

**Verificação rápida:** registre um caso que funciona, um caso que falha e o que você mudaria.

## Vocabulário para explicar em voz alta

- **Por que separar adaptador do provedor?** Para trocar modelo sem alterar a lógica do produto.
- **O que fazer com timeout?** Tratar a falha, aplicar retry limitado quando seguro e informar o usuário.
- **Onde guardar a API key?** Em variável de ambiente ou gerenciador de segredos.

## Erro comum

Concluir a etapa apenas por ter assistido ao vídeo. A conclusão exige explicar a ideia, executar o exercício e verificar um resultado observável.

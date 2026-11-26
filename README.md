# Plano de estudos: engenharia de software com IA aplicada

Trilha original, gratuita para leitura, em português, organizada para quem **já conhece desenvolvimento de software, mas está começando em Python**. O material reúne fundamentos, exercícios progressivos, questionários após cada etapa e flashcards por módulo. Os cursos das fontes podem exigir inscrição ou pagamento; este plano usa links como referência, sem reproduzir suas aulas.

## Como usar

Dedique 6 a 8 horas por semana: ~40% leitura e vídeo, ~50% prática e ~10% revisão. A estimativa total é de **146 horas** (aproximadamente 20 semanas a 8 horas/semana; ajuste conforme seu ritmo). Faça os módulos em sequência; o projeto final reutiliza todas as entregas. Em cada módulo, leia `aula.md`, execute `pratica.md`, responda ao `questionario.md` por etapa e revise `flashcards.md` em 1, 3, 7 e 14 dias. O gabarito está recolhido no questionário.

## Mapa dos módulos

| Módulo | Tempo | Fase |
|---|---:|---|
| [00 — Python, Git e ambiente](00-python-git-e-ambiente/) | 8 h | Fundamentos |
| [01 — Engenharia de software com IA](01-engenharia-de-software-com-ia/) | 8 h | Fundamentos |
| [02 — LLMs, tokens e prompts](02-fundamentos-llm-e-prompts/) | 10 h | Fundamentos |
| [03 — APIs e aplicativos inteligentes](03-apis-e-apps-inteligentes/) | 10 h | Fundamentos |
| [04 — RAG: busca, recuperação e citações](04-rag-busca-e-citacoes/) | 14 h | Construção |
| [05 — Agentes e uso de ferramentas](05-agentes-e-ferramentas/) | 12 h | Construção |
| [06 — MCP: protocolo e integrações](06-mcp-protocolo-e-integracoes/) | 12 h | Construção |
| [07 — LangGraph: estado e orquestração](07-langgraph-orquestracao-e-estado/) | 14 h | Construção |
| [08 — Hermes Agent e OpenClaw](08-hermes-e-openclaw/) | 8 h | Construção |
| [09 — Avaliação, segurança e observabilidade](09-avaliacao-seguranca-e-observabilidade/) | 12 h | Produção |
| [10 — Fine tuning: quando fazer](10-fine-tuning-e-decisao/) | 12 h | Produção |
| [11 — Deploy, LLMOps e custo](11-deploy-llmops-e-custo/) | 10 h | Produção |
| [12 — Projeto final: assistente de documentação](12-projeto-final/) | 16 h | Produção |

## Projeto transversal

Crie gradualmente um assistente de documentação: primeiro a especificação, depois API, recuperação com fontes, agente com ferramenta, MCP, fluxo em LangGraph e avaliação. Use documentos públicos ou criados por você; não inclua dados de clientes, chaves ou documentos protegidos no repositório.

## Qual técnica escolher?

| Necessidade observada | Primeira tentativa | Evidência para mudar |
|---|---|---|
| Formato ou resposta instável | Prompt, exemplos, validação | Erros persistentes em conjunto de teste |
| Informação privada ou atualizada | Busca/RAG com fonte | Recuperação insuficiente após ajuste e avaliação |
| Executar consulta ou ação | API/ferramenta; MCP para interoperabilidade | Erros de contrato ou permissões |
| Fluxo com rotas, estado ou aprovação | Workflow/LangGraph | Complexidade demonstrada no fluxo |
| Comportamento especializado repetido | Fine tuning com dados de qualidade | Ganho medido versus prompt/RAG, custo justificável |

**Fine tuning** não é o primeiro recurso para ensinar fatos novos: comece medindo um baseline e prefira RAG para conteúdo que muda ou exige citação. No módulo 10 há uma decisão experimental com conjunto de teste separado.

## Fontes de inspiração e extensão

- [Asimov: Vibe Coding](https://www.asimov.academy/trilhas/vibe-coding/) — visão, jornadas, documentação e construção assistida.
- [Asimov: Aplicações Inteligentes](https://www.asimov.academy/trilhas/aplicacoes-inteligentes-com-ia/) — aplicações, modelos, memória, interface e deploy.
- [Asimov: Hermes Agent](https://www.asimov.academy/trilhas/hermes-agent/) — ferramentas, skills, MCP e automações.
- [Asimov: OpenClaw](https://www.asimov.academy/trilhas/openclaw/) — workspace, memória e agentes pessoais.
- [UNIPDS: código e referências da pós](https://github.com/unipds-engenharia-de-ia-aplicada/engenharia-de-software-com-ia-aplicada) — fundamentos, APIs, MCP, agentes, arquitetura, segurança e fine tuning.
- [UNIPDS: página da pós](https://unipds.com.br/org-pos-ia/) — contexto do programa; a grade operacional foi contrastada com o repositório público, sem afirmar equivalência curricular.

Este repositório é independente das instituições acima. Links externos podem mudar; ferramentas e APIs também. Consulte sempre a documentação oficial atual antes de instalar ou integrar.

## Próximo passo

Abra [00 — Python, Git e ambiente](00-python-git-e-ambiente/README.md). Conclua o programa de contagem de palavras e responda às seis questões antes de iniciar o módulo 01.

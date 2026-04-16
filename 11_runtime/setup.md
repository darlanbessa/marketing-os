# SETUP DA MÁQUINA

## Objetivo
Executar os agentes do Marketing OS de forma organizada, com memória, workflows e possibilidade de automação.

## Componentes
- Repositório GitHub com os agentes
- Modelo de IA via API
- Runtime/orquestrador
- Memória operacional
- Scheduler para rodar automaticamente

## APIs necessárias
Escolher uma:
- OpenAI API
- Anthropic API
- Gemini API

## Estrutura mínima recomendada
- GitHub: guardar agentes e workflows
- OpenClaw ou ferramenta similar: executar agentes
- SQLite ou arquivo local: memória inicial
- n8n, cron ou GitHub Actions: automação

## Ordem de funcionamento
1. Objetivo entra
2. Maestro escolhe workflow
3. Agentes executam em sequência
4. Resultado é salvo em memory.md
5. Próxima execução usa o histórico

## Prioridade atual
1. Organizar runtime
2. Testar workflow manual
3. Conectar API
4. Automatizar tarefas recorrentes

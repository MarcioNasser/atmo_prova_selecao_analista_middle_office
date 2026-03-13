Implementação do pipeline end-to-end ANA

Implementação completa da prova técnica end-to-end ANA, incluindo:

- parsing robusto de datas e números pt-BR
- parser HTML ANA com deduplicação por record_id
- normalização e validação de registros
- persistência idempotente em SQLite
- geração de artefatos operacionais e checkpoint
- scheduler
- API FastAPI
- análise com métricas e interpretação
- testes automatizados

Validação local:
- pytest -q: 112 passed

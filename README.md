# projeto-analisador-sentimentos


Projeto desenvolvido em Python para a Análise de Sentimento automatizada de feedbacks de clientes,
classificando reviews em sentimentos (Positivo, Neutro ou Negativo) e estabelecendo um fluxo de trabalho de monitoramento da satisfação.

O sistema demonstra proficiência em Classificação de Texto (NLP), Arquitetura Modular e rotinas de Validação Humana (Human-in-the-Loop).

## Tecnologias
- Python
- SQLite
- SQL


## Funcionalidades
- Registro e Classificação: Inclusão de novos feedbacks com análise de sentimento automática.
- Correção Humana (Ground Truth): Permite rotular o Sentimento Real para calibração do modelo.
- Relatório de Acurácia: Cálculo do desempenho do modelo (Predito vs. Real).
- Re-análise em Lote: Re-aplicação da classificação do modelo a todo o histórico de reviews.


## Como executar
python main.py
### Fluxo de Uso Recomendado:
- Inserir: Menu [1] Gerenciar Feedbacks -> [1] Adicionar Novo Feedback.
- Validar: Menu [1] Gerenciar Feedbacks -> [3] Corrigir/Validar Sentimento.
- Relatar: Menu [2] Analisar Sentimento (ML) -> [2] Gerar Relatório de Acurácia.

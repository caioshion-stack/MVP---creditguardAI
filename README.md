# MVP - CreditGuardAI
Este repositório contém um Modelo Viável de Produto (MVP) para análise e gestão de risco de cobrança baseado em dados reais de clientes.
## Objetivo
Fornecer uma solução simples para classificar clientes em grupos de risco (Alto/Baixo) com base no histórico de atrasos e comportamento de pagamento, auxiliando na priorização e estratégias de cobrança.
## Conteúdo do Repositório
- `clientes.csv` - Dados dos clientes com informações de faturas, atrasos e pagamentos.
- `analise_risco.ipynb` - Notebook com análise, classificação de risco, visualizações e geração de relatórios.
- `clientes_alto_risco.csv` - Relatório gerado com clientes classificados como de alto risco (atualizado conforme análise).
## Como usar
### Método 1: Usar no Google Colab diretamente
1. Abra o notebook `analise_risco.ipynb` no Google Colab via link:
https://colab.research.google.com/github/caioshion-stack/MVP---creditguardAI/blob/main/analise_risco.ipynb

2. Certifique-se de que o arquivo `clientes.csv` está no repositório (pasta raiz).
3. Execute as células do notebook na ordem, que:
- Carregam os dados
- Fazem a classificação de risco
- Geram visualizações
- Exportam o arquivo `clientes_alto_risco.csv`
4. Baixe qualquer arquivo gerado para seu computador usando os comandos de download no Colab.
---
### Método 2: Rodar localmente (requer Python e pandas)
1. Clone este repositório:
 https://github.com/caioshion-stack/MVP---creditguardAI.git cd MVP---creditguardAI
2. Instale as dependências necessárias

3. Abra o Jupyter Notebook localmente e execute o `analise_risco.ipynb`.
---


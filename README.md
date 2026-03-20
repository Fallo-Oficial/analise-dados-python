# 📈 - Análise de Dados de Cancelamento

Projeto desenvolvido para analisar uma base de mais de 800 mil clientes para identificar os principais motivos de cancelamento (churn) e propor soluções baseadas em dados.

## 🚀 Tecnologias Utilizadas
* **Python** para lógica de programação.
* **Pandas** para limpeza e manipulação de grandes bases de dados.
* **Plotly Express** para criação de gráficos de análise visual.
* **Jupyter Notebook (.ipynb)** para documentação do passo a passo.

## 🔍 Insights Identificados
Através das visualizações geradas, identificamos padrões críticos que influenciam o cancelamento:

1. **Tipo de Contrato:** Clientes com contrato mensal possuem uma taxa de cancelamento altíssima em comparação aos trimestrais e anuais.

2. **Atendimento (Call Center):** Clientes que ligam mais de 4 vezes para o suporte têm uma tendência quase total de cancelamento.

3. **Atrasos:** Clientes com atrasos no pagamento superiores a 20 dias representam uma grande parte das perdas.

## 💡 Soluções Propostas
Com base na análise, as recomendações para a empresa são:

* **Incentivar contratos longos:** Oferecer descontos para migrar clientes do mensal para o anual.

* **Prioridade no Suporte:** Criar um alerta para clientes que chegam à 3ª ligação para resolver o problema antes do cancelamento.

* **Gestão de Cobrança:** Implementar lembretes automáticos para pagamentos antes dos 20 dias de atraso.

## 🛠️ Como rodar o projeto
1. **Certifique-se de ter o Python e o VS Code instalados.**

2. **Instale as bibliotecas necessárias:**

    ```bash
    pip install pandas plotly openpyxl nbformat ipykernel
    ```

3. **Abra o arquivo `python_insights.ipynb` e execute as células.**
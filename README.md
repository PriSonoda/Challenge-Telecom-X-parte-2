📊 Telecom X – Parte 2
Previsão de churn e análise dos fatores de evasão

🎯 Objetivo
Prever o churn de clientes com base em variáveis relevantes, identificar os fatores que mais influenciam a evasão e apoiar estratégias de retenção usando modelos de Machine Learning.

📁 Estrutura do Projeto
- notebook.ipynb – análise completa, EDA, preparação dos dados e modelos
- /data – arquivos CSV tratados
  
🔧 Preparação dos Dados
- Variáveis numéricas: tenure, MonthlyCharges, TotalCharges
- Variáveis categóricas: Contract, PaymentMethod, InternetService etc.
- Aplicação de One-Hot Encoding
- Normalização das variáveis numéricas
- Separação em treino e teste
- Escolhas feitas para permitir que todos os modelos lidassem corretamente com escalas e categorias
  
📊 EDA – Principais Insights
- Contratos mensais têm maior risco de churn
- Clientes com pouco tempo de contrato cancelam mais
- Electronic Check aparece com maior taxa de evasão
- Valores mensais altos aumentam o risco
- Gráficos usados: distribuição de churn, boxplots, barras por contrato, heatmap
  
🤖 Modelos Utilizados
Regressão Logística, KNN, Decision Tree e Random Forest (melhor desempenho geral).

▶️ Como Executar
Bibliotecas necessárias: pandas, numpy, seaborn, matplotlib, scikit-learn
- Baixe ou clone o repositório
- Abra o notebook.ipynb
- Carregue os arquivos da pasta /data
- Execute as células na ordem


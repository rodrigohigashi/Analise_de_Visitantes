🛍️ Shopping Center Visitor Analysis / Análise de Visitantes em Shopping Centers
📋 Overview / Visão Geral

This project analyzes visitor behavior in shopping centers based on gender, age, annual income, and spending score.
Este projeto analisa o comportamento dos visitantes em shopping centers com base em gênero, idade, renda anual e score de consumo.

Through exploratory data analysis and visualizations, we extract actionable insights to understand visitor profiles and preferences.
Através de análise exploratória e visualizações de dados, são obtidos insights para compreender melhor os perfis e preferências dos visitantes.

🚀 Key Features / Principais Recursos

✔ Exploratory Data Analysis / Análise Exploratória de Dados — Detailed exploration of variables and relationships / Exploração detalhada das variáveis e suas relações
✔ Interactive Visualizations / Visualizações Interativas — Charts that reveal behavior patterns / Gráficos que evidenciam padrões de comportamento
✔ Business Insights / Insights de Negócio — Identification of visitor segments based on income and spending score / Identificação de segmentos de visitantes com base em renda e score

🧰 Technologies / Tecnologias Utilizadas

Python

Pandas — Data manipulation and cleaning / Manipulação e limpeza de dados

NumPy — Numerical operations support / Suporte a operações numéricas

Matplotlib / Seaborn — Data visualization / Visualização de dados

Scikit-Learn — Used for clustering tests (future projects) / Usado para testes de agrupamento (projetos futuros)

📂 Project Structure / Estrutura do Projeto
notebooks/
├── EN/
│   ├── Visitor_Analysis.ipynb
│   └── README_EN.md
└── PT/
    ├── Analise_de_Visitantes.ipynb
    └── README_PT.md
data/
└── clientes_shopping.csv
requirements.txt
README.md  <- (this file / este arquivo)

⚙️ How to Run / Como Executar

1️⃣ Clone the repository / Clone o repositório:
```
git clone https://github.com/rodrigohigashi/Data_Analysis.git
cd Data_Analysis
```

2️⃣ Create a virtual environment and install dependencies / Crie um ambiente virtual e instale as dependências:

python -m venv venv
venv\Scripts\activate  # Windows
# or / ou
source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt


3️⃣ Run the notebook / Execute o notebook:

jupyter notebook notebooks/EN/Visitor_Analysis.ipynb  # EN
jupyter notebook notebooks/PT/Analise_de_Visitantes.ipynb  # PT

📊 Main Insights / Principais Insights

📌 Female visitors represent the majority of the audience / Visitantes do sexo feminino representam a maior parte do público

📌 The predominant income range is R$50,000–R$85,000 per year / Faixa de renda predominante está entre R$50.000 e R$85.000 anuais

📌 Positive relationship observed between annual income and spending score / Relação positiva entre renda anual e score de consumo

🎯 Learnings / Aprendizados

This project highlights the importance of exploratory data analysis as a key step to understand consumer behavior and support effective marketing strategies.
Este projeto reforça a importância da análise exploratória como etapa essencial para compreender o comportamento do consumidor e apoiar estratégias de marketing mais assertivas.

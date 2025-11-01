# 🛍️ Análise de Visitantes em Shopping Centers

## 📋 Visão Geral
Este projeto tem como objetivo analisar o comportamento dos visitantes em shopping centers com base em variáveis como gênero, idade, renda anual e pontuação de consumo (*spending score*).  
Através de técnicas de análise exploratória e visualização de dados, foram obtidos insights que ajudam a entender melhor o perfil dos consumidores e suas preferências.

## 🚀 Principais Recursos
✔ **Análise Exploratória:** Exploração detalhada das variáveis e suas relações.  
✔ **Visualizações Interativas:** Gráficos que evidenciam padrões de comportamento.  
✔ **Insights de Negócio:** Identificação de segmentos de visitantes com base em renda e score.  

## 🧰 Tecnologias Utilizadas
- **Python**
- **Pandas** — Manipulação e limpeza de dados  
- **Matplotlib / Seaborn** — Visualização de dados  
- **NumPy** — Suporte a operações numéricas  
- **Scikit-Learn** — Usado para testes de agrupamento (em projetos futuros)

## 📂 Estrutura do Projeto
notebooks/
└── PT/
├── Analise_de_Visitantes.ipynb
└── README_PT.md
data/
└── clientes_shopping.csv

## ⚙️ Como Executar
1️⃣ Clone o repositório:
```bash
git clone https://github.com/rodrigohigashi/Data_Analysis.git
cd Data_Analysis
2️⃣ Crie o ambiente virtual e instale as dependências:

python -m venv venv
venv\Scripts\activate  # Windows
# ou
source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt
3️⃣ Execute o notebook:

jupyter notebook notebooks/PT/Analise_de_Visitantes.ipynb
📊 Principais Insights
📌 Visitantes do sexo feminino representam a maior parte do público.
📌 A faixa de renda predominante está entre R$ 50.000 e R$ 85.000 anuais.
📌 A análise mostra relação positiva entre renda anual e score de consumo.

🎯 Aprendizados
Este projeto reforça a importância da análise exploratória como etapa essencial para compreender o comportamento do consumidor e apoiar estratégias de marketing mais assertivas.
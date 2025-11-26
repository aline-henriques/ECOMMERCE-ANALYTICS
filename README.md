# 🛍️ E-commerce Analytics — Olist Dataset

**Análise estatística e exploratória de dados de e-commerce brasileiro**  
Projeto desenvolvido para a disciplina **Estatística e Probabilidade**, **Cesar School (2025.2)**  

## Índice
 
1. [🎯 Objetivo](#-objetivo)  
2. [📂 Estrutura do Projeto](#-estrutura-do-projeto)  
3. [🧠 Tecnologias Utilizadas](#-tecnologias-utilizadas)  
4. [🧩 Como Reproduzir a Análise?](#-como-reproduzir-a-análise?)  
5. [📈 Resultados Principais](#-resultados-principais)  
6. [📄 Relatório Completo](#-relatório-completo)  
7. [👩‍💻 Equipe](#-equipe) 

---

## 🎯 Objetivo

Realizar uma **análise estatística e exploratória (EDA)** do *Brazilian E-Commerce Public Dataset by Olist* (Kaggle), respondendo perguntas de negócio relacionadas a:
- Receita, ticket médio e descontos  
- Custos e participação do frete  
- Prazos e atrasos de entrega  
- Conversão e comportamento do cliente  

---

## 📂 Estrutura do Projeto

```

ecommerce-analytics/
├── data/                          # Dados originais (Olist)
├── notebooks/
│   └── analise_olist.ipynb        # Notebook completo da análise
├── reports/
│   ├── relatorio_analitico_olist.md
│   └── relatorio_analitico_olist.pdf   # 📄 Relatório final (PDF)
└── README.md

````

---

## 🧠 Tecnologias Utilizadas
- **Python 3.11**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **SciPy**, **Statsmodels**
- **Jupyter Notebook**, **VS Code**

---

## 🧩 Como Reproduzir a Análise?

1️⃣ Clone o repositório:
```bash
git clone https://github.com/seu-usuario/ecommerce-analytics.git
cd ecommerce-analytics
````

2️⃣ Crie o ambiente virtual:

```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```

3️⃣ Abra o notebook:

```bash
jupyter notebook notebooks/analise_olist.ipynb
```

4️⃣ Para gerar o relatório novamente:

```bash
pandoc reports/relatorio_analitico_olist.md -o reports/relatorio_analitico_olist.pdf --standalone
```

---

## 📈 Resultados Principais

* 💰 Ticket médio: **R$ 310,00**
* 🚚 Frete médio: **R$ 18,70** (~12% do total)
* ⏰ 7,5% dos pedidos com atraso
* 🗺️ Região Sudeste com maior volume e ticket
* 💳 Conversão de pagamento: **98,8%**

---

## 📄 Relatório Completo

📥 [**Clique aqui para abrir o relatório em PDF**](https://github.com/aline-henriques/ECOMMERCE-ANALYTICS/blob/4702b7506a4cacafa23c26f6873621c9eae714fc/%F0%9F%A7%BERelat%C3%B3rio%20Anal%C3%ADtico%20%E2%80%94%20Ecommerce%20Brasileiro%20(Olist).pdf)

> O relatório completo inclui análise descritiva, inferência estatística, gráficos, KPIs e insights de negócio.

---

## 👩‍💻 Equipe
- **Aline de Albuquerque Henriques**
- **Bruno Felipe de Castilho**
- **Thyalles Campos de Araújo**

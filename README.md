# 🎬 Movie Analytics & IMDB Rating Prediction  
# 🎬 Análise de Filmes & Predição de Nota IMDB

---

## 📌 Overview | Visão Geral

🇺🇸  
This project performs an end-to-end Data Analysis and Machine Learning pipeline on a movie dataset, aiming to extract business insights and build a regression model capable of predicting IMDB ratings.

🇧🇷  
Este projeto realiza uma análise completa de dados (end-to-end) e modelagem preditiva em um conjunto de dados de filmes, com o objetivo de extrair insights de negócio e construir um modelo de regressão capaz de prever notas do IMDB.

The workflow includes:
- Data cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Statistical correlation analysis  
- Predictive modeling  
- Model evaluation  

---

## 🎯 Business Context | Contexto de Negócio

🇺🇸  
In the entertainment industry, predicting audience reception supports:

- Investment decisions  
- Marketing strategies  
- Content positioning  
- Revenue forecasting  

This project investigates:

- What drives higher IMDB ratings?  
- Does popularity influence ratings?  
- Do genre and certification impact audience perception?  
- Can we predict IMDB ratings using structured features?  

🇧🇷  
Na indústria do entretenimento, prever a recepção do público auxilia:

- Decisões de investimento  
- Estratégias de marketing  
- Posicionamento de conteúdo  
- Projeções de receita  

Este projeto investiga:

- Quais fatores estão associados a notas mais altas?  
- Popularidade influencia a avaliação?  
- Gênero e classificação indicativa impactam a percepção?  
- É possível prever notas do IMDB com variáveis estruturadas?  

---

## 📊 Dataset Description | Descrição do Dataset

The dataset contains structured information about movies, including:

- Title | Título  
- Release Year | Ano de lançamento  
- Runtime | Duração  
- Genre | Gênero  
- Certificate | Classificação indicativa  
- IMDB Rating | Nota IMDB  
- Meta Score | Nota da crítica  
- Number of Votes | Número de votos  
- Gross Revenue | Receita bruta  

### 🎯 Target Variable | Variável Alvo

`IMDB_Rating`

---

## 🔎 Exploratory Data Analysis (EDA) | Análise Exploratória

🇺🇸 Key Findings:

- Ratings concentrate between **7.6 and 8.3**  
- Number of votes shows moderate positive correlation (0.318)  
- Meta Score correlates positively (0.271)  
- Revenue strongly correlates with popularity (0.54)  
- Drama is the most frequent genre  
- Log transformation improved skewed distributions  

🇧🇷 Principais Resultados:

- As notas concentram-se entre **7,6 e 8,3**  
- Número de votos apresenta correlação positiva moderada (0,318)  
- Meta Score possui correlação positiva (0,271)  
- Receita tem forte correlação com popularidade (0,54)  
- Drama é o gênero mais frequente  
- Transformação logarítmica reduziu assimetria  

---

## 🧠 Feature Engineering | Engenharia de Atributos

- Log transformation of `No_of_Votes`  
- One-hot encoding for Genre and Certificate  
- Selection of relevant numerical features  
- Removal of non-predictive textual fields  

🇧🇷  

- Transformação logarítmica em `No_of_Votes`  
- One-hot encoding para Gênero e Classificação  
- Seleção de variáveis numéricas relevantes  
- Remoção de atributos textuais não preditivos  

---

## 🤖 Machine Learning Model | Modelo de Machine Learning

### Problem Type | Tipo de Problema

Supervised Regression | Regressão Supervisionada  

### Model Used | Modelo Utilizado

Linear Regression (Scikit-Learn)  

### Evaluation Metric | Métrica de Avaliação

`RMSE (Root Mean Squared Error)`

### Performance | Desempenho

`RMSE ≈ 0.256`

🇺🇸  
On average, predictions differ by approximately 0.26 IMDB points.

🇧🇷  
Em média, as previsões diferem cerca de 0,26 pontos da nota real.

---

## 🎥 Example Prediction | Exemplo de Predição

Movie | Filme:

`The Shawshank Redemption`

Predicted | Previsto:

`9.02`

Actual | Real:

`9.3`

---

## 🏗 Project Structure | Estrutura do Projeto

```
movie-analytics-imdb/
│
├── movie_analysis_imdb.ipynb
├── model.pkl
├── Relatorio_Tecnico-Data_Science.pdf
├── requirements.txt
└── README.md
```

---

## 🛠 Technologies Used | Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- NLTK  
- WordCloud  

---

## 🚀 How to Run | Como Executar

### 1️⃣ Clone the repository | Clone o repositório

```bash
git clone https://github.com/MarcoCostaSilva/movie-analytics-imdb.git
cd movie-analytics-imdb
```

### 2️⃣ Install dependencies | Instale as dependências

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the notebook | Execute o notebook

Open:

`movie_analysis_imdb.ipynb`

Run all cells to reproduce the analysis and model.

---

## 📌 Future Improvements | Melhorias Futuras

- Cross-validation  
- Random Forest / Gradient Boosting comparison  
- Hyperparameter tuning  
- Feature importance analysis  
- API deployment with FastAPI  
- Streamlit dashboard  

---

## 🧩 Skills Demonstrated | Competências Demonstradas

✔ Data Cleaning  
✔ Exploratory Data Analysis  
✔ Feature Engineering  
✔ Statistical Interpretation  
✔ Regression Modeling  
✔ Model Evaluation  
✔ Business-Oriented Insights  

---

## 👤 Author

Marco Aurélio Costa da Silva  
Data Scientist | Data-Oriented Full Stack Developer | Statistical Modeling  

GitHub: https://github.com/MarcoCostaSilva  
LinkedIn: https://linkedin.com/in/marco-costadasilva  
Academic CV (Lattes Platform – Brazil): https://lattes.cnpq.br/8887305754672433



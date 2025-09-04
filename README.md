# 🎬 Desafio Ciência de Dados – Indicium (Bolsa Lighthouse 2025)

Este repositório contém minha solução para o **Desafio de Ciência de Dados** proposto pela Indicium.  
O objetivo é analisar um dataset de filmes do IMDB e desenvolver um modelo preditivo para auxiliar um estúdio de Hollywood a decidir qual tipo de filme deve ser produzido.

---

## 📂 Estrutura do Repositório

```

├── modeloRegressão.ipynb   
├── modelo\_imdb.pkl         
├── requirements.txt        
├── reports/
│   └── analise.pdf         
└── README.md               

````

---

## 🚀 Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/ArthurWgirao/desafio_Indicium.git
   cd desafio_Indicium


2. (Opcional) Crie um ambiente virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o notebook no Jupyter ou Google Colab:

   ```bash
   jupyter notebook modeloRegressão.ipynb
   ```

5. Consulte o relatório final em:

   ```
   reports/analise.pdf
   ```


## 📊 O que está em cada arquivo?

* **modeloRegressão.ipynb** → código completo de análise exploratória, gráficos e modelagem.
* **modelo\_imdb.pkl** → modelo de regressão treinado salvo em formato `.pkl`.
* **requirements.txt** → lista de pacotes necessários para execução.
* **reports/analise.pdf** → relatório final contendo:

  * Respostas às perguntas do desafio.
  * Insights da análise exploratória (EDA).
  * Interpretação dos resultados do modelo.

---

## 💾 Modelo

Para carregar o modelo salvo:

```python
import joblib

model = joblib.load("modelo_imdb.pkl")
```

---

## 🛠️ Tecnologias utilizadas

* Python 3.12
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Joblib

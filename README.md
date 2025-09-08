# Análise de Sobrevivência dos Passageiros do Titanic

## 📌 Sobre o Projeto
Este projeto consiste em uma análise exploratória de dados do naufrágio do Titanic, desenvolvida como atividade acadêmica da disciplina de **Ciência de Dados**.  
O objetivo é identificar os principais fatores que influenciaram a sobrevivência dos passageiros através de técnicas de **pré-processamento, análise estatística e visualização de dados**.

---

## 🎯 Objetivos
- Realizar **tratamento de dados** (valores ausentes e variáveis categóricas)  
- Aplicar **análise descritiva** (tendência central, dispersão e distribuição)  
- Criar **visualizações gráficas** para interpretação dos padrões  
- Identificar **fatores determinantes** para a sobrevivência  

---

## 📊 Dataset
- **Fonte**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)  
- **Passageiros**: 891  
- **Variáveis**: 12 colunas (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked)  

---

## 🛠️ Tecnologias Utilizadas
- **Python 3.12**  
- **Pandas** → Manipulação e análise de dados  
- **NumPy** → Operações numéricas  
- **Matplotlib** → Visualizações gráficas  
- **Seaborn** → Visualizações estatísticas  
- **Scikit-learn** → Pré-processamento (LabelEncoder)  

---

## 📈 Metodologia

### 1️⃣ Pré-processamento
- **Dados ausentes**:  
  - Idade → preenchida com mediana  
  - Porto de embarque → preenchido com moda  
  - Cabine → removida (77% de valores ausentes)  
- **Variáveis categóricas** → convertidas em numéricas com LabelEncoder  

### 2️⃣ Análise Exploratória
- Estatísticas descritivas (média, mediana, desvio padrão)  
- Distribuição de frequências  
- Análises cruzadas (sobrevivência × gênero × classe social)  

### 3️⃣ Visualização
- Histogramas e gráficos de distribuição  
- Boxplots para comparação entre grupos  
- Gráficos de dispersão para correlações  
- Gráficos de barras e pizza para frequências relativas  

---

## 📊 Principais Insights

### 🔹 Sobrevivência Geral
- **61.6%** não sobreviveram  
- **38.4%** sobreviveram  

### 🔹 Fator Gênero (mais determinante)
- **Mulheres**: 74.2% de sobrevivência  
- **Homens**: 18.9% de sobrevivência  

### 🔹 Fator Classe Social
- **1ª Classe**: 63.0% sobreviveram  
- **2ª Classe**: 47.3% sobreviveram  
- **3ª Classe**: 24.2% sobreviveram  

### 🔹 Fator Econômico
- **Sobreviventes**: tarifa média de **$48.40**  
- **Não-sobreviventes**: tarifa média de **$22.12**  

---

## ▶️ Como Executar

1. **Clone o repositório**
```bash
git clone https://github.com/Vanessa-Matias/titanic_analysis.git
cd titanic_analysis
``` 

2. **Instale as dependências**
```bash
pip install -r requirements.txt
```

3. **Execute a análise**
```bash
jupyter notebook notebooks/titanic_analysis.ipynb
``` 
📊 Resultados

A análise revelou que gênero, classe social e poder econômico foram os fatores mais determinantes para a sobrevivência, refletindo as desigualdades sociais e políticas de salvamento da época.

👩‍💻 Autora

Vanessa Matias - Estudante de Análise e Desenvolvimento de Sistemas

📝 Licença

Este projeto é para fins educacionais.
Os dados são disponibilizados pelo Kaggle para competições de machine learning.

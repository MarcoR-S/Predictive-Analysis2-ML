# Análise Preditiva de Solo e Colheita

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Este repositório contém o desenvolvimento do modelo de Machine Learning da **FarmTech Solutions**. O objetivo principal do projeto é realizar a análise das condições do solo e aplicar modelos preditivos para otimizar e prever métricas essenciais na colheita de cana-de-açúcar, comparando os impactos e eficiências dos métodos de colheita **manual** e **mecânica**.

## 📌 Visão Geral do Projeto

O agronegócio moderno exige tomadas de decisão baseadas em dados (Data-Driven). Este projeto aborda o ciclo completo de uma solução de Ciência de Dados aplicada ao campo: desde o tratamento de dados brutos do solo até a construção e avaliação de modelos preditivos capazes de antecipar o rendimento da safra e indicar os melhores caminhos para o manejo da lavoura.

### Principais Funcionalidades:
* **Análise Exploratória de Dados (EDA):** Investigação detalhada de variáveis do solo (nutrientes, umidade, PH) e fatores climáticos.
* **Comparativo de Impacto:** Análise estatística e preditiva comparando a colheita manual e a colheita mecânica.
* **Modelagem Preditiva:** Implementação de algoritmos de Machine Learning para previsão de produtividade da cana-de-açúcar.
* **Engenharia de Recursos (Feature Engineering):** Tratamento de dados ausentes, normalização e codificação de variáveis categóricas.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python** utilizando o ambiente do Jupyter Notebook. As principais ferramentas envolvidas foram:

* **Manipulação e Análise de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Machine Learning (Modelagem e Avaliação):** `scikit-learn`

---

## 📊 Estrutura do Pipeline de ML

O arquivo principal `ProjetoConclusãoML.ipynb` está dividido nas seguintes etapas competitivas:

1.  **Carregamento e Limpeza dos Dados:** Identificação de outliers, tratamento de valores nulos e consistência dos dados agrícolas.
2.  **Análise Exploratória:** Gráficos de correlação e distribuição para entender o comportamento das lavouras de cana-de-açúcar.
3.  **Pré-processamento:** Divisão entre conjuntos de treino e teste, além de técnicas de escala (ex: `StandardScaler` ou `MinMaxScaler`).
4.  **Treinamento de Modelos:** Aplicação de algoritmos de regressão/classificação para estimar os resultados da colheita.
5.  **Avaliação de Performance:** Análise de métricas de erro (como RMSE, MAE e $R^2$) ou métricas de classificação (Acurácia, F1-Score) para validar a eficácia do modelo no mundo real.

---

## 🚀 Como Executar o Projeto

Se quiser rodar este notebook localmente na sua máquina, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
   cd seu-repositorio

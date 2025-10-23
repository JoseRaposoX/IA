# Aplicação de Inteligência Artificial na Especulação de Criptomoedas

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.3-orange?logo=scikitlearn)
![Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-green)

## Sobre o Projeto

Este projeto demonstra, de forma prática e educativa, como **modelos de Inteligência Artificial (IA)** podem ser aplicados na **análise e previsão de tendências do preço do Bitcoin (BTC)**.

Através de técnicas de *Machine Learning* supervisionado, o modelo tenta prever se o preço do Bitcoin no **próximo dia** terá **tendência de alta (1)** ou **baixa (0)**, com base em dados históricos e indicadores técnicos.


---

## Objetivos

- Demonstrar o uso de IA na especulação de criptomoedas  
- Aplicar técnicas de *machine learning supervisionado*  
- Explorar dados históricos reais obtidos via **Yahoo Finance**  
- Analisar o desempenho do modelo com métricas clássicas  

---

## Metodologia

1. **Coleta de Dados:** via biblioteca `yfinance`  
2. **Pré-processamento:** cálculo de indicadores técnicos como:
   - `Return (%)` — variação percentual diária  
   - `MA5` e `MA10` — médias móveis de 5 e 10 dias  
   - `RSI` — índice de força relativa (Relative Strength Index)
3. **Criação da Variável Alvo:**  
   - `1` → preço de fechamento do dia seguinte maior (subida)  
   - `0` → preço de fechamento menor (queda)
4. **Modelo Utilizado:**  
   - `DecisionTreeClassifier` (Scikit-learn)
5. **Avaliação:**  
   - Acurácia  
   - Matriz de Confusão  
   - *Precision*, *Recall* e *F1-score*

---

## 🧩 Estrutura do Projeto
📂 crypto-ia-project/
│

├── 📘 Trabalho_IA_Especulacao_Criptomoedas.docx # Relatório completo do projeto

├── 🤖 crypto_ia.ipynb # Notebook com o código (Google Colab)

├── 📈 resultados.png # Visualização dos resultados (opcional)

  |── README.md # Este arquivo

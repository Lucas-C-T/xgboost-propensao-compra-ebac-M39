# Projeto de Propensão a Compra - XGBoost

## 🎯 Objetivo
Este projeto tem como objetivo aplicar técnicas de Machine Learning para prever a propensão de compra de carros por clientes. Através de uma base de dados específica, o foco é realizar o pré-processamento necessário, treinar um modelo **XGBoost** e identificar as variáveis que mais influenciam na decisão de compra.

## 🛠️ Tecnologias Utilizadas
- Python 3.9+
- Pandas, NumPy
- Scikit-learn (LabelEncoder, Model Selection, Metrics)
- XGBoost
- Matplotlib, Seaborn

## 📊 Metodologia
1. **Exploração dos dados**: Carregamento da base, verificação de tipos e identificação de valores nulos.
2. **Limpeza e Tratamento**: Remoção da coluna de identificação (`User ID`) e validação estatística inicial dos dados.
3. **Feature Engineering**: Aplicação de `LabelEncoder` para converter a variável categórica `Gender` em numérica.
4. **Modelagem**: Implementação do algoritmo XGBoost para classificação.
5. **Análise**: Geração da matriz de correlação para identificar os principais preditores da variável *target* (`Purchased`).

# 📊 Projeto de Regressão Logística — Previsão de Cliques em Anúncios

## 📌 Sobre o projeto

Este projeto aplica **Regressão Logística** para prever se um usuário da internet irá ou não clicar em um anúncio publicitário, com base em características comportamentais e demográficas.

O objetivo é construir um modelo de classificação capaz de identificar o perfil de usuários mais propensos a interagir com anúncios — uma aplicação direta em contextos de marketing digital e análise de comportamento do consumidor.

---

## 🗂️ Sobre os dados

O dataset contém informações de usuários com as seguintes variáveis:

| Variável | Descrição |
|---|---|
| `Daily Time Spent on Site` | Tempo diário no site (minutos) |
| `Age` | Idade do usuário |
| `Area Income` | Renda média da região do usuário |
| `Daily Internet Usage` | Uso médio diário de internet (minutos) |
| `Male` | Gênero (1 = masculino) |
| `Clicked on Ad` | Variável alvo: 1 = clicou, 0 = não clicou |

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 🔍 Etapas do projeto

1. **Importação e exploração dos dados** — análise inicial com `info()` e `describe()`
2. **Análise exploratória (EDA)** — histogramas, jointplots e pairplot para entender distribuições e correlações
3. **Treinamento do modelo** — divisão treino/teste com `train_test_split` e ajuste do modelo de Regressão Logística
4. **Avaliação** — relatório de classificação com métricas de precisão, recall e F1-score

---

## 📈 Resultados

O modelo de Regressão Logística apresentou bom desempenho na classificação de usuários, demonstrando que variáveis como **tempo no site**, **idade** e **uso de internet** são fortes indicadores do comportamento de clique.

---

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/projeto-regressao-logistica.git

# Instale as dependências
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Execute o notebook
jupyter notebook projeto-de-regressao-logistica.ipynb
```

---

## 👩‍💻 Sobre mim

Estou em transição de carreira para a área de Dados e este projeto faz parte do meu portfólio de aprendizado prático em Machine Learning.

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/fernanda-carvalho-martins/)!

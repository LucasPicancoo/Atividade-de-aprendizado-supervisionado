# Previsão de Valores Imobiliários com Modelos de Machine Learning

Este projeto realiza a previsão do valor médio de casas (MEDV) utilizando o conjunto de dados Boston Housing. Foram testados dois modelos de regressão: Rede Neural Artificial (MLPRegressor) e Random Forest, com comparação de desempenho entre eles.

---

## 📁 Estrutura do Projeto

- **Pré-processamento:** Tratamento de valores ausentes, normalização dos dados e engenharia de features.
- **Modelagem:** Treinamento e avaliação de modelos de regressão usando MLPRegressor e Random Forest.
- **Avaliação:** Uso das métricas MAE, RMSE e R² para comparar a performance dos modelos.
- **Visualização:** Gráficos de evolução do erro, importância das variáveis e comparação entre valores reais e previstos.

---

## 🚀 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## ⚙️ Como Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências (recomendado usar um ambiente virtual):
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o script principal:
   ```bash
   python main.py
   ```

---

## 📊 Resultados

| Métrica | RNA (MLPRegressor) | Random Forest |
|--------:|--------------------:|---------------:|
| MAE     | 2.24                | 2.06           |
| RMSE    | 3.46                | 2.80           |
| R²      | 0.84                | 0.89           |

- O modelo **Random Forest** apresentou melhor desempenho geral.
- As variáveis mais importantes foram **RM**, **LSTAT** e **PTRATIO**.

---

## 📈 Visualizações Incluídas

- Curva de perda durante o treinamento da RNA
- Gráfico de dispersão: valores reais vs. previstos
- Gráfico de importância das variáveis (Random Forest)
- Comparativo de desempenho entre modelos

---

## 👤 Colaboradores

- Rafael Portugal
- Lucas Picanço
- Matheus Ribas
- Marco Decco
- Victor Hugo

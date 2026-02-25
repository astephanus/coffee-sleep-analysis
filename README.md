# Análise do Consumo de Café e Qualidade do Sono

A empresa Health&Life Analytics deseja entender como o consumo de café influencia a qualidade do sono dos clientes e se é possível prever a qualidade do sono com base em hábitos e características individuais.

O objetivo foi transformar dados brutos em insights estratégicos e em um modelo preditivo aplicável ao negócio.

---

## Perguntas Respondidas

- Existe relação entre consumo de café e horas de sono?
- O nível de estresse influencia mais o sono do que o café?
- É possível prever a qualidade do sono com base nos hábitos dos clientes?
- Qual modelo apresenta melhor desempenho preditivo?

---

## Etapas do Projeto

### Parte 1 — Análise Exploratória (EDA)
- Estatísticas descritivas
- Análise de valores nulos
- Histogramas e boxplots
- Análise de variáveis categóricas
- Testes estatísticos (ANOVA)

### Parte 2 — Visualizações Comparativas
- Segmentação por gênero
- Relação entre idade, estresse e consumo de café
- Criação da feature derivada `Coffee_Category`
- Identificação de padrões estratégicos

### Parte 3 — Modelagem Preditiva
- Pré-processamento dos dados
- Codificação de variáveis categóricas
- Divisão treino/teste
- Treinamento de dois modelos:
  - Regressão Logística
  - Random Forest
- Avaliação com:
  - Acurácia
  - Matriz de Confusão
  - Classification Report
- Identificação de leve overfitting no Random Forest

---

## Principais Resultados

- O nível de estresse apresentou forte impacto na duração do sono.
- Clientes com alto consumo de café dormem, em média, cerca de 36 minutos a menos por noite.
- O Random Forest apresentou melhor acurácia (97%), com leve overfitting.
- A Regressão Logística apresentou maior estabilidade entre treino e teste.

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Como Executar

1. Instale as dependências: pip install pandas numpy matplotlib seaborn scikit-learn joblib
2. Execute o notebook no Jupyter ou Google Colab.

---

## Arquivos do Projeto

- `notebook_projeto.ipynb`
- `synthetic_coffee_health_10000.csv`
- `dataset_processado_sleep_quality.csv`
- `modelo_random_forest_sleep_quality.pkl`

---

## Observação sobre o modelo salvo

O modelo Random Forest foi salvo localmente como `modelo_random_forest_sleep_quality.pkl`.

Devido a limitações de tamanho do GitHub para arquivos binários, o modelo não foi incluído neste repositório. Ele pode ser regenerado executando o notebook completo.

## Conclusão

O projeto demonstra a capacidade de conduzir uma análise completa, desde exploração de dados até modelagem preditiva e geração de recomendações estratégicas para o negócio.


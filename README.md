# 💼 Portfólio de Data Science — Rian Freires

Bem-vindo ao meu portfólio de projetos em Data Science! Aqui você encontrará aplicações práticas em classificação, regressão, clusterização, deep learning e deploy de modelos. Estes projetos foram desenvolvidos com foco em resolução de problemas reais, análise de dados e construção de soluções inteligentes.

---

## 📁 Projetos

---

### 🔢 **Classificação — Previsão de Churn de Clientes Bancários**

Este projeto tem como objetivo prever quais clientes de um banco têm maior probabilidade de cancelar seus serviços (churn), utilizando técnicas de machine learning supervisionado.

🔍 **Objetivos principais:**

* Identificar padrões de comportamento de clientes que levam ao cancelamento.
* Auxiliar o banco a tomar decisões estratégicas para retenção de clientes.
* Avaliar modelos preditivos com foco em recall e AUC-ROC.

⚙️ **Principais etapas:**

* **EDA detalhada:** análise de correlações, valores ausentes, balanceamento de classes e impacto das variáveis como idade, saldo e satisfação.
* **Pré-processamento:** codificação de variáveis categóricas, normalização de numéricas e balanceamento com técnicas como SMOTE.
* **Modelagem:** comparação entre Random Forest, XGBoost e Regressão Logística.
* **Avaliação:** uso de métricas como AUC-ROC, F1-Score, Matriz de Confusão, importância de variáveis.
* **Resultados:** Identificação de clientes de risco e sugestões de estratégias de retenção.

🔗 [Ver projeto](https://github.com/Riansito/Analise-_de_Churn_CLientes)

---

### 📈 **Regressão — Previsão de Custos de Seguros Médicos**

O objetivo deste projeto é construir um modelo capaz de prever os custos com seguros médicos de pacientes com base em fatores como idade, IMC, tabagismo e região.

🔍 **Objetivos principais:**

* Prever o custo estimado de seguro com boa precisão.
* Entender o impacto de fatores comportamentais e demográficos no custo.
* Oferecer uma base para políticas de precificação mais justas por seguradoras.

⚙️ **Principais etapas:**

* **EDA e visualizações:** análises gráficas (boxplots, scatterplots, heatmaps) para entender relação entre custo e variáveis como idade e tabagismo.
* **Modelos utilizados:** Regressão Linear, Decision Tree Regressor, Random Forest, Gradient Boosting.
* **Ajuste de Hiperparâmetros:** RandomizedSearchCV para melhoria de performance.
* **Métricas:** MAE, MSE e R² para avaliação dos modelos.
* **Insights:** Fumantes e pacientes mais velhos apresentam custos significativamente mais altos.

🔗 [Ver projeto](https://github.com/Riansito/Analise-de-Custos-de-Seguro-Saude-Modelagem-Preditiva)

---
Claro! Aqui está uma versão do seu projeto de **precificação de carros usados** seguindo o mesmo padrão:

---

### 🚗 **Regressão/Cluster — Precificação de Carros Usados**

O objetivo deste projeto é construir um modelo capaz de prever o preço de carros usados com base em características como ano, quilometragem, avaliações de motoristas, tipo de combustível, transmissão, tração e clusters de veículos.

🔍 **Objetivos principais:**

* Prever o preço estimado de carros usados com boa precisão.
* Entender o impacto de características do veículo e do mercado no preço.
* Oferecer insights sobre segmentação de veículos para suporte a decisões de compra, venda e marketing.

⚙️ **Principais etapas:**

* **Limpeza e preparação de dados:** tratamento de valores faltantes, outliers, codificação de variáveis categóricas.
* **EDA e visualizações:** análise detalhada de preços, quilometragem, ano e avaliações, utilizando gráficos como boxplots, histogramas e heatmaps.
* **Clusterização de veículos:** uso de K-Means para criar clusters como Carros Premium, Carros Custo-Benefício, Carros Luxos e Carros Populares. Os clusters foram usados também como **variáveis explicativas na regressão**, ajudando o modelo a capturar perfis de veículos.
* **Modelos utilizados:** Decision Tree Regressor, Random Forest, XGBoost, LGBM e Stacking Regressor.
* **Ajuste de Hiperparâmetros:** RandomizedSearchCV para otimização de cada modelo, melhorando métricas como RMSE, MAE e R².
* **Métricas:** avaliação com R², RMSE, MAE e MSE para comparar performance dos modelos.
* **Insights:** veículos mais recentes e com baixa quilometragem são consistentemente mais caros; clusters ajudam a diferenciar perfis de mercado e melhoram a previsão do preço.

🔗 [Ver projeto](https://github.com/Riansito/Precificacao_Carros_ML.git)

---

### 🧠 **Visão Computacional (CNN) — Classificador de Pneumonia por Imagem de Raio-X**

Neste projeto, desenvolvi uma rede neural convolucional (CNN) para classificar imagens de raio-X como **NORMAL** ou **PNEUMONIA**, com deploy via Flask e interface amigável para médicos ou pacientes.

🔍 **Objetivos principais:**

* Apoiar o diagnóstico médico por meio de análise automatizada de imagens.
* Criar uma interface web simples para upload de imagem e envio de resultado.
* Facilitar o acesso a uma ferramenta de triagem com custo reduzido.

⚙️ **Principais etapas:**

* **Arquitetura da CNN:** camadas convolucionais, pooling, dropout e ativação sigmoide na saída.
* **Dataset utilizado:** Chest X-Ray Images (Pneumonia).
* **Treinamento:** fit nos dados de treino e validação
* **Interface web:** formulário para cadastro, upload de imagem e envio de resultado por e-mail.
* **Deploy local:** com Flask, usando o modelo `.h5` treinado.

🔗 [Ver projeto](https://github.com/Riansito/Classificacao-de-Raio-X-Pneumonia-Normal)

---

### 📟 **End-to-End — Previsão de Inadimplência de Empréstimos com Deploy Web**

Projeto completo desde o tratamento dos dados até o deploy final de um modelo de previsão de inadimplência de clientes em uma aplicação web.

🔍 **Objetivos principais:**

* Construir um pipeline completo de ciência de dados.
* Prever clientes inadimplentes e permitir o uso prático via interface web.
* Tornar o modelo acessível para uso em decisões de crédito.

⚙️ **Principais etapas:**

* **Análise exploratória e limpeza dos dados.**
* **Feature engineering:** seleção de variáveis importantes e transformação de variáveis categóricas.
* **Modelos utilizados:** Decision Trees, Random Forest, XGBoost.
* **Avaliação:** Acurácia, recall, matriz de confusão e curva ROC.
* **Deploy:** Flask com formulário web que retorna o risco de inadimplência em tempo real.

🔗 [Ver projeto](https://github.com/Riansito/End_To_End_Emprestimos)

---

## ⚙️ Tecnologias e Ferramentas

* **Linguagens:** Python, HTML/CSS
* **Bibliotecas:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, TensorFlow/Keras, Flask
* **Técnicas:** Classificação, Regressão, Clusterização, CNN, Deploy com Flask, EDA, Validação Cruzada
* **Outros:** Git, GitHub, Deploy local, RandomizedSearchCV, GridSearchCV

---

## 🌐 Contato

* 📧 Email: [rianfreires@gmail.com](mailto:rianfreires@gmail.com)
* 🔗 LinkedIn: [linkedin.com/in/rianfreires](www.linkedin.com/in/rian-freires-da-costa-silva-798813324)
* 📊 [Portfólio Power BI](https://sites.google.com/view/portifliorianpowerbi/in%C3%ADcio)
* 📃 [Portfólio Excel](https://sites.google.com/view/portiflioexcelrian/in%C3%ADcio)

---

> *"Transformando dados em decisões inteligentes com tecnologia e propósito."* 🚀

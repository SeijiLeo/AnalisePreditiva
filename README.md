# 📊 Previsão de Churn – TelecomX

## 🚀 Visão Geral do Projeto

Neste projeto desenvolvi um modelo preditivo para identificar clientes com alto risco de evasão (churn) em uma empresa de telecomunicações.

O churn é um dos principais problemas estratégicos do setor, impactando diretamente a receita, custo de aquisição e crescimento sustentável. A proposta foi transformar dados históricos em um modelo capaz de antecipar cancelamentos e gerar insights acionáveis para retenção.

---

## 🎯 Problema de Negócio

Empresas de telecom possuem alto custo de aquisição de clientes (CAC).  
Reter um cliente é significativamente mais barato do que conquistar um novo.

A pergunta central foi:

> **É possível prever quais clientes têm maior probabilidade de cancelar o serviço?**

Se sim, a empresa pode:
- Criar campanhas direcionadas
- Oferecer incentivos personalizados
- Reduzir churn de forma estratégica
- Aumentar o Lifetime Value (LTV)

---

## 📂 Dados Utilizados

O dataset contém informações sobre:

- Perfil demográfico
- Tipo de contrato
- Serviços contratados
- Forma de pagamento
- Tempo de permanência
- Valor mensal
- Status de churn (variável alvo)

---

## 🔎 Etapas do Projeto

### 1️⃣ Análise Exploratória (EDA)

Principais descobertas:

- 📌 Clientes com contrato mensal apresentam maior churn.
- 📌 Baixo tempo de permanência é um forte indicador de cancelamento.
- 📌 Pagamentos automáticos estão associados a menor evasão.
- 📌 Serviços adicionais (segurança online, suporte técnico) reduzem churn.

Essa etapa permitiu entender padrões comportamentais antes da modelagem.

---

### 2️⃣ Preparação dos Dados

- Remoção de variáveis irrelevantes (`CustomerID`)
- Padronização de categorias
- Encoding de variáveis categóricas
- Divisão treino/teste
- Normalização (para modelos sensíveis à escala)

---

## 🤖 Modelagem Preditiva

Modelos testados:

- Árvore de Decisão  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Regressão Logística  

### 🎯 Critérios de Avaliação

- Acurácia
- Precisão
- Recall
- F1-score
- Comparação treino vs teste (overfitting)

---

## 🏆 Modelo Final

O **Random Forest** apresentou o melhor equilíbrio entre:

- Performance
- Generalização
- Robustez contra overfitting

Além disso, permitiu análise de importância das variáveis.

---

## 📊 Principais Variáveis Preditivas

As variáveis com maior impacto na previsão de churn foram:

- Tipo de contrato
- Tempo de permanência
- Valor mensal
- Forma de pagamento
- Serviços adicionais

Essas informações são extremamente valiosas para estratégias de retenção.

---

## 💡 Impacto Estratégico

Com base nos resultados, a empresa poderia:

- 🎯 Criar campanhas para clientes nos primeiros meses
- 🎯 Incentivar migração para contratos anuais
- 🎯 Oferecer benefícios para pagamento automático
- 🎯 Criar bundles de serviços adicionais
- 🎯 Implementar monitoramento contínuo de risco de churn

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📈 Próximos Passos

- Ajuste de hiperparâmetros (GridSearch)
- Balanceamento de classes (SMOTE)
- Teste com XGBoost / LightGBM
- Deploy do modelo como API
- Dashboard interativo para área de negócios

---

## 📌 O Que Este Projeto Demonstra

✔ Capacidade de estruturar um problema de negócio  
✔ Análise exploratória orientada a insights  
✔ Pipeline completo de Machine Learning  
✔ Avaliação crítica de modelos  
✔ Interpretação estratégica dos resultados  

---

## 👤 Sobre Mim

Sou um profissional da área de tecnologia, formado em ADS e me aprofundando em DataScience e CyberSecurity.

Este projeto foi criado para um Challenge proposto para o meu curso da ALura OracleG9 na formação de DataScience, ele mostra minha capacidade de realizar análises técnicas com impacto real de negócio.

Caso goste do projeto e queira conversar sobre dados, machine learning ou oportunidades, estou disponível!

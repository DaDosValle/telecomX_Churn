# Análise de dados de Churn em Telecomunicações – TelecomX

## 📌 Visão Geral

Este projeto tem como objetivo analisar os principais fatores associados à **evasão de clientes (churn)** em uma empresa fictícia de telecomunicações, utilizando **Python**, técnicas de **ETL** e **Análise Exploratória de Dados (EDA)**. A análise é orientada a negócio, com foco em gerar **insights acionáveis para retenção de clientes**.

Projeto desenvolvido com nível **Júnior ** para o programa ONE (Oracle e Alura), demonstrando domínio prático de manipulação, análise e interpretação de dados.

---

## 🎯 Problema de Negócio

A evasão de clientes representa impacto direto na receita e no crescimento sustentável de empresas de telecomunicações. O desafio deste projeto foi responder à seguinte pergunta:

> **Quais são os principais fatores que influenciam o churn, considerando variáveis categóricas e numéricas?**

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Consumo de API
* Matplotlib / Seaborn
* Google Colab

---

## 🔄 Pipeline de Dados (ETL)

### Extração

* Coleta de dados a partir de uma API
* Dados em formato **JSON aninhado**

### Transformação

* Normalização da estrutura JSON
* Tratamento de valores nulos
* Conversão de tipos de dados
* Padronização de variáveis categóricas

### Carga

* Estruturação dos dados em formato tabular para análise

---

## 📊 Análise Exploratória de Dados (EDA)

A EDA foi conduzida comparando clientes que **permaneceram** e **sairam**, explorando:

### Variáveis Categóricas

* Tipo de contrato
* Serviços adicionais
* Forma de pagamento
* Suporte técnico

### Variáveis Numéricas

* Tempo de permanência (tenure)
* Valor mensal
* Total gasto pelo cliente

---

## 💡 Principais Insights

* Clientes com **contratos mensais** apresentam maior taxa de churn
* **Valores mensais elevados** estão associados a maior evasão
* **Menor tempo de permanência** indica maior risco de churn
* Clientes sem **suporte técnico** tendem a evadir mais
* Fatores contratuais e percepção de valor são determinantes para retenção

---

## 📈 Recomendações de Negócio

* Incentivar a migração para contratos de longo prazo
* Revisar estratégias de precificação de planos premium
* Investir em suporte técnico como diferencial competitivo
* Criar ações preventivas para clientes com alto risco de churn

---

## 🚀 Próximos Passos

* Construção de modelo preditivo de churn (Regressão Logística)
* Aplicação de testes estatísticos para validação dos achados
* Criação de dashboard interativo para acompanhamento de métricas

---

## 📁 Estrutura do Repositório

```
├── Resumo_executivo_telecon-x_churn
├── ETL_EDA_TELECOMX.ipynb
├── README.md
```

---

## 👤 Autor

**Fernando do Valle**
📧 Contato: [Meu e-mail](fsf.dovalle@gmail.com)
💼 LinkedIn: [Meu LinkedIn](https://www.linkedin.com/in/fernando-do-valle/)

---

⭐ *Se este projeto foi útil, fique à vontade para deixar uma estrela no repositório!*


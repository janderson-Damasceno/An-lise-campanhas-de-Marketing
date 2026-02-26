# 📊 Análise de Dados e Performance de Marketing

Este projeto apresenta uma análise completa de um banco de dados de marketing, contemplando desde o tratamento dos dados brutos até a construção de um dashboard interativo no Microsoft Power BI, com foco em geração de insights estratégicos para apoio à tomada de decisão.

---

## 📁 Sobre os Dados

A base utilizada (`dados_marketing.csv`) contém informações de clientes coletadas entre 2018 e 2023.

### 🔎 Principais Variáveis

**Perfil do Cliente**

* ID do cliente
* Ano de nascimento
* Escolaridade
* Estado civil
* País de residência

**Dados Econômicos**

* Salário anual
* Número de filhos e adolescentes no domicílio

**Comportamento de Consumo**

* Gastos em:

  * Eletrônicos
  * Brinquedos
  * Móveis
  * Utilidades
  * Alimentos
  * Vestuário

**Canais e Engajamento**

* Compras realizadas via:

  * Web
  * Catálogo
  * Lojas físicas
* Participação em 5 campanhas de marketing anteriores

---

## 🛠️ Pipeline do Projeto

### 1️⃣ Processamento e Limpeza de Dados (ETL)

Os dados foram extraídos de um arquivo CSV com delimitador ponto e vírgula (`;`).

As etapas de tratamento incluíram:

* Padronização de datas (ex: 07/01/2020)
* Tratamento de valores nulos
* Correção de tipos de dados (numéricos, categóricos e datas)
* Padronização de informações geográficas
* Organização das colunas para modelagem analítica

Essa etapa garantiu consistência, confiabilidade e qualidade das informações para análise.

---

### 2️⃣ Modelagem e Visualização no Power BI (Mini-Projeto1.pbix)

No Microsoft Power BI, foram criados indicadores estratégicos (KPIs) e visuais interativos para facilitar a análise gerencial.

O dashboard foi estruturado com foco em:

### 📌 Segmentação

Análise do comportamento de compra por nível de escolaridade (Graduação, Mestrado, Doutorado).

### 📌 Conversão

Comparação da taxa de sucesso da campanha mais recente em relação às campanhas anteriores.

### 📌 Preferência de Canal

Identificação do canal mais utilizado para finalização da compra versus número de visitas ao site.

---

## 💡 Insights Estratégicos e Tomada de Decisão

O dashboard permite apoiar decisões como:

### 🎯 Personalização de Ofertas

Direcionamento de campanhas de Eletrônicos para clientes de alta renda e maior escolaridade, que apresentam maior ticket médio nessa categoria.

### 🌍 Otimização de Orçamento

Identificação de países com menor engajamento para ajustes estratégicos, além de realocação de investimentos para mercados mais rentáveis, como Espanha e Estados Unidos.

### 💰 Estratégia de Descontos

Análise do impacto do número de compras com desconto na fidelização dos clientes, avaliando se a estratégia gera recorrência ou apenas vendas pontuais com menor margem.

---

## 🚀 Tecnologias Utilizadas

* Microsoft Power BI — Modelagem de dados, DAX e criação do dashboard
* CSV / Excel — Armazenamento e estruturação inicial dos dados

---



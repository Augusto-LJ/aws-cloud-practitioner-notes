# 📊 Amazon Redshift

## 📌 O que é

O Amazon Redshift é um serviço de **data warehouse totalmente gerenciado** da AWS.

Ele é projetado para **análise de grandes volumes de dados (analytics)** utilizando consultas SQL de alta performance.

---

## 🎯 Quando usar

- Análise de grandes volumes de dados (Big Data)
- Business Intelligence (BI)
- Relatórios e dashboards
- Data analytics (ex: consultas complexas)

---

## ⚙️ Como funciona

- Armazena dados em formato **colunar**
- Utiliza **SQL** para consultas
- Processa dados de forma distribuída (cluster)

---

## 📦 Conceitos importantes

### 🧱 Data Warehouse
- Banco otimizado para análise (não para transações)

---

### 🖥️ Cluster
- Conjunto de nós que processam dados

---

### ⚙️ Node (nó)
- Unidade de processamento dentro do cluster

---

### 📊 Armazenamento colunar
- Dados armazenados por coluna (não por linha)
- Melhor performance para consultas analíticas

---

### ⚡ Processamento Massivamente Paralelo (MPP)
- Executa consultas em paralelo
- Alta performance para grandes volumes

---

## 💰 Modelo de cobrança

Você paga por:

- Tempo de uso dos nós (cluster)
- Armazenamento
- Transferência de dados

---

## 🔗 Integração

- Amazon S3
- Amazon RDS
- Amazon DynamoDB
- Ferramentas de BI (ex: Power BI, Tableau)

---

## 🔒 Segurança

- Integração com IAM
- Criptografia em repouso e em trânsito
- Controle de acesso

---

## ⚖️ Comparações importantes

### Redshift vs RDS

| Redshift | RDS |
|----------|-----|
| Data warehouse | Banco relacional |
| Foco em análise | Foco em transações |
| Grandes volumes | Operações do dia a dia |
| Alta performance analítica | OLTP |

---

### Redshift vs DynamoDB

| Redshift | DynamoDB |
|----------|-----------|
| Analítico (OLAP) | Operacional (NoSQL) |
| SQL | NoSQL |
| Dados estruturados | Dados flexíveis |
| Consultas complexas | Baixa latência |

---

### Redshift vs S3

| Redshift | S3 |
|----------|----|
| Consulta com SQL | Armazenamento de arquivos |
| Data warehouse | Data lake |
| Processamento interno | Armazena dados |

---

## 🧠 Conceitos importantes para prova

- Redshift = data warehouse
- Foco em análise (OLAP)
- Usa SQL
- Armazenamento colunar
- Processamento paralelo (MPP)

---

## ⚠️ Pegadinhas comuns

- Não é para aplicações transacionais (OLTP)
- Não substitui banco relacional tradicional
- Não é NoSQL
- Não é apenas armazenamento (como S3)

---

## 🔁 Resumo rápido

- Redshift = data warehouse da AWS
- Ideal para análise de grandes dados
- Alta performance com SQL
- Usa armazenamento colunar e processamento paralelo

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Redshift
- [ ] Sei diferença entre OLTP e OLAP
- [ ] Entendo conceito de data warehouse
- [ ] Sei quando usar Redshift vs RDS/DynamoDB

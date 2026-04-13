# 🔄 AWS Database Migration Service (DMS)

## 📌 O que é

O AWS DMS (Database Migration Service) é um serviço que permite **migrar bancos de dados para a AWS de forma rápida e segura**.

Ele suporta migrações com **mínimo downtime**, mantendo a aplicação funcionando durante o processo.

---

## 🎯 Quando usar

- Migrar banco on-premises para AWS
- Migrar entre bancos iguais (ex: PostgreSQL → RDS PostgreSQL)
- Migrar entre bancos diferentes (ex: Oracle → Aurora)
- Combinar diferentes bancos em um só
- Replicação contínua de dados
- Modernização de aplicações

---

## ⚙️ Como funciona

1. Conecta ao banco de origem
2. Conecta ao banco de destino
3. Copia os dados
4. (Opcional) Continua replicando mudanças em tempo real

---

## 📦 Conceitos importantes

### 📤 Source (origem)
- Banco de dados atual

---

### 📥 Target (destino)
- Banco de dados para onde os dados vão

---

### 🔄 Replicação contínua (CDC - Change Data Capture)
- Captura mudanças no banco de origem
- Replica em tempo real no destino

---

### 🖥️ Replication Instance
- Instância gerenciada pela AWS que executa a migração

---

## 🔄 Tipos de migração

### 🟢 Full Load
- Migração completa dos dados

---

### 🟡 CDC (Change Data Capture)
- Migração contínua após carga inicial

---

### 🔵 Full Load + CDC
- Carga inicial + sincronização em tempo real

---

## 🔗 Integração

- Amazon RDS
- Amazon Aurora
- Amazon DynamoDB
- Bancos on-premises

---

## 💰 Benefícios

- Baixo downtime
- Suporte a múltiplos bancos
- Migração segura
- Processo automatizado

---

## ⚖️ Comparações importantes

### DMS vs Backup/Restore

| DMS | Backup |
|-----|--------|
| Migração contínua | Cópia pontual |
| Baixo downtime | Pode ter downtime |
| Replicação em tempo real | Não |

---

### DMS vs ETL

| DMS | ETL |
|-----|-----|
| Migração | Transformação de dados |
| Foco em mover dados | Foco em transformar |
| Simples | Mais complexo |

---

## 🧠 Conceitos importantes para prova

- DMS = migração de banco de dados
- Suporta CDC (replicação contínua)
- Baixo downtime
- Usa replication instance

---

## ⚠️ Pegadinhas comuns

- Não faz transformação complexa (isso é ETL)
- Não é banco de dados
- Não substitui ferramentas de analytics
- Pode precisar de outra ferramenta para conversão de schema

---

## 🔁 Resumo rápido

- DMS = migração de bancos para AWS
- Suporta replicação em tempo real
- Minimiza downtime
- Funciona entre diferentes engines

---

## 📌 Status de aprendizado

- [ ] Entendo o que é DMS
- [ ] Sei o que é CDC
- [ ] Entendo como funciona a migração
- [ ] Sei quando usar DMS

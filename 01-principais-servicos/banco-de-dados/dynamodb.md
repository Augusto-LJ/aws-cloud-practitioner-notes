# 🗃️ DynamoDB

## 📌 O que é

O DynamoDB é um serviço serverless de banco de dados **NoSQL totalmente gerenciado** da AWS.

Ele oferece alta performance, baixa latência e escalabilidade automática para aplicações que precisam lidar com grandes volumes de dados.

---

## 🎯 Quando usar

- Aplicações com alto volume de requisições
- Sistemas que precisam de baixa latência
- Dados não estruturados ou semi-estruturados
- Aplicações modernas (ex: serverless, APIs)

---

## ⚙️ Como funciona

- Armazena dados em **tabelas**
- Cada item é identificado por uma **chave primária**
- Não exige schema fixo (flexível)

---

## 📦 Conceitos importantes

### 📋 Tabela
- Estrutura principal onde os dados são armazenados

---

### 🔑 Chave primária
Pode ser:
- **Partition Key** (chave simples)
- **Partition Key + Sort Key** (chave composta)

---

### 📄 Item
- Registro dentro da tabela (equivalente a uma linha)

---

### 🧩 Atributo
- Campos do item (equivalente a colunas)

---

### 📈 Escalabilidade automática
- Ajusta capacidade automaticamente conforme demanda

---

### ⚡ Baixa latência
- Respostas em milissegundos

---

## 💰 Modelo de cobrança

Você paga por:
- Leitura e escrita (capacidade provisionada ou sob demanda)
- Armazenamento
- Recursos adicionais (ex: backups)

---

## 🔒 Segurança

- Controle via IAM
- Criptografia em repouso
- Integração com outros serviços AWS

---

## ⚖️ Comparações importantes

### DynamoDB vs RDS

| DynamoDB | RDS |
|----------|-----|
| NoSQL | Relacional (SQL) |
| Schema flexível | Schema fixo |
| Escalabilidade automática | Escalabilidade mais limitada |
| Alta performance | Mais complexo |

---

### DynamoDB vs S3

| DynamoDB | S3 |
|----------|----|
| Banco de dados | Armazenamento de objetos |
| Consulta rápida | Armazenamento de arquivos |
| Baixa latência | Alta durabilidade |

---

## 🧠 Conceitos importantes para prova

- DynamoDB = banco NoSQL
- Escalabilidade automática
- Baixa latência
- Schema flexível
- Usa chave primária para acesso

---

## ⚠️ Pegadinhas comuns

- Não usa SQL tradicional
- Não é ideal para relacionamentos complexos
- Modelagem é diferente de banco relacional
- Pode ser caro se mal configurado

---

## 🔁 Resumo rápido

- DynamoDB = banco NoSQL gerenciado
- Alta performance e escalabilidade
- Ideal para aplicações modernas
- Sem necessidade de gerenciamento de infraestrutura

---

## 📌 Status de aprendizado

- [ ] Entendo o que é DynamoDB
- [ ] Sei diferença entre NoSQL e relacional
- [ ] Entendo chave primária
- [ ] Sei quando usar DynamoDB vs RDS

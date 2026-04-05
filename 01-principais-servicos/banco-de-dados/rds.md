# 🗄️ RDS (Relational Database Service)

## 📌 O que é

O RDS (Relational Database Service) é um serviço gerenciado da AWS para bancos de dados relacionais.

Ele facilita a configuração, operação e escalabilidade de bancos de dados na nuvem.

---

## 🎯 Quando usar

- Aplicações que utilizam banco de dados relacional (SQL)
- Sistemas que precisam de consistência e integridade (ACID)
- Quando não quer gerenciar infraestrutura de banco manualmente

---

## ⚙️ Como funciona

- Você escolhe o mecanismo do banco
- Define configurações (CPU, memória, armazenamento)
- AWS cuida de:
  - Provisionamento
  - Backup
  - Atualizações
  - Alta disponibilidade (opcional)

---

## 📦 Mecanismos de banco suportados

O RDS suporta diversos bancos de dados relacionais:

- Amazon Aurora
- PostgreSQL
- MySQL
- MariaDB
- Oracle
- Microsoft SQL Server

---

### ⭐ Amazon Aurora
- Banco relacional otimizado pela AWS
- Compatível com MySQL e PostgreSQL
- Melhor performance e escalabilidade

---

## ⚙️ Conceitos importantes

### 🧱 Instância de banco
- Ambiente onde o banco roda
- Equivalente a um servidor de banco

---

### 💾 Armazenamento
- Baseado em EBS
- Escalável conforme necessidade

---

### 📸 Backup automático
- AWS realiza backups automáticos
- Permite restauração em ponto no tempo (Point-in-Time Recovery)

---

### 🔄 Multi-AZ
- Replica síncrona em outra AZ
- Alta disponibilidade e failover automático

---

### 📖 Read Replicas
- Réplicas para leitura
- Melhoram performance de consultas

---

## 💰 Modelo de cobrança

Você paga por:
- Tempo de instância (CPU/memória)
- Armazenamento
- Backups adicionais
- Transferência de dados

---

## 🔒 Segurança

- Controle via IAM
- Integração com VPC
- Criptografia em repouso e em trânsito

---

## ⚖️ Comparações importantes

### RDS vs DynamoDB

| RDS | DynamoDB |
|-----|----------|
| Relacional (SQL) | Não relacional (NoSQL) |
| Estrutura fixa (schema) | Schema flexível |
| ACID | Alta escalabilidade |

---

### RDS vs EC2 (banco gerenciado vs não gerenciado)

| RDS | EC2 |
|-----|-----|
| Gerenciado pela AWS | Você gerencia tudo |
| Backup automático | Backup manual |
| Atualizações automáticas | Você atualiza |

---

## 🧠 Conceitos importantes para prova

- RDS = banco relacional gerenciado
- Suporta vários mecanismos (MySQL, PostgreSQL, etc.)
- Multi-AZ = alta disponibilidade
- Read Replica = melhora leitura
- Backup automático incluso

---

## ⚠️ Pegadinhas comuns

- RDS não é NoSQL
- Multi-AZ ≠ Read Replica
- RDS não dá controle total do sistema operacional
- Aurora é diferente (e otimizado)

---

## 🔁 Resumo rápido

- RDS = banco relacional gerenciado
- Suporte a vários engines
- Backup automático e alta disponibilidade
- Fácil de escalar e operar

---

## 📌 Status de aprendizado

- [ ] Entendo o que é RDS
- [ ] Conheço os mecanismos suportados
- [ ] Entendo Multi-AZ e Read Replicas
- [ ] Sei diferença entre RDS e DynamoDB

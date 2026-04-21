# 🚨 AWS Budgets

## 📌 O que é

O AWS Budgets é um serviço que permite **definir limites de gastos e uso na AWS e receber alertas quando esses limites são atingidos ou previstos**.

Ele ajuda a evitar surpresas na fatura.

---

## 🎯 Quando usar

- Controlar custos da AWS
- Evitar gastos inesperados
- Monitorar uso de recursos
- Definir limites por projeto ou equipe

---

## ⚙️ Como funciona
<img width="1080" height="407" alt="image" src="https://github.com/user-attachments/assets/ff071968-1a7d-4da2-9df3-614f800b094f" />

- Você define um orçamento (budget)
- Configura um limite (ex: $100/mês)
- Define alertas (ex: 80%, 100%)
- As informações do AWS Budgets são atualizadas três vezes por dia
- Recebe notificações quando atingir ou prever atingir o limite

---

## 📦 Tipos de orçamento

### 💰 Cost Budget (Orçamento de custo)
- Baseado em valor gasto (ex: $50/mês)

---

### 📊 Usage Budget (Orçamento de uso)
- Baseado no uso de recursos
- Ex: horas de EC2, GB armazenados

---

### 📉 Reservation Budget
- Acompanha utilização de instâncias reservadas

---

### 🧩 Savings Plans Budget
- Monitora uso e cobertura de Savings Plans

---

## 🔔 Alertas

- Enviados por:
  - Email
  - SNS (Simple Notification Service)

---

### 📈 Tipos de alerta

- Baseado em **uso atual**
- Baseado em **previsão (forecast)**

---

## 🔗 Integração

- AWS Cost Explorer (dados de custo)
- AWS Organizations (controle por contas)
- Amazon SNS (notificações)

---

## ⚖️ Comparações importantes

### AWS Budgets vs Cost Explorer

| AWS Budgets | Cost Explorer |
|-------------|---------------|
| Define limites | Analisa custos |
| Envia alertas | Não envia alertas |
| Controle proativo | Análise reativa |

---

### AWS Budgets vs Billing Dashboard

| AWS Budgets | Billing Dashboard |
|-------------|------------------|
| Alertas | Visualização |
| Limites definidos | Resumo da fatura |
| Proativo | Informativo |

---

## 🧠 Conceitos importantes para prova

- Budgets = controle com alertas
- Permite limites de custo e uso
- Pode usar previsão (forecast)
- Integra com SNS

---

## ⚠️ Pegadinhas comuns

- Confundir com Cost Explorer
- Achar que impede gastos (não impede, apenas alerta)
- Não usar alertas de previsão
- Achar que é automático (precisa configurar)

---

## 🔁 Resumo rápido

- Budgets = definir limites
- Envia alertas
- Pode prever gastos
- Ajuda a controlar custos

---

## 📌 Status de aprendizado

- [ ] Entendo o que é AWS Budgets
- [ ] Sei criar limites de custo
- [ ] Entendo alertas e forecast
- [ ] Sei diferença para Cost Explorer

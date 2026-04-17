# 📣 Amazon SNS (Simple Notification Service)

## 📌 O que é

O Amazon SNS é um serviço de **mensageria baseado em publicação/assinatura (pub/sub)**.

Permite enviar mensagens para múltiplos destinos simultaneamente.

---

## 🎯 Quando usar

- Notificações em massa
- Comunicação com múltiplos sistemas
- Integração com diferentes serviços

---

## ⚙️ Como funciona

- Um produtor publica uma mensagem em um tópico
- Todos os assinantes recebem essa mensagem

---

## 📦 Conceitos importantes

### 📌 Tópico (Topic)
- Canal de comunicação
- Onde mensagens são publicadas

---

### 👥 Assinantes (Subscribers)
- Destinos que recebem mensagens
- Exemplos:
  - SQS
  - Lambda
  - HTTP endpoints
  - E-mail
  - SMS

---

## 🚀 Casos de uso

- Envio de notificações
- Alertas de sistema
- Integração entre serviços
- Fan-out (um para muitos)

---

## 💰 Benefícios

- Entrega rápida
- Alta escalabilidade
- Integração com vários serviços

---

## ⚖️ Comparações importantes

### SNS vs SQS

| SNS | SQS |
|-----|-----|
| Pub/Sub | Fila |
| Múltiplos consumidores | 1 consumidor |
| Entrega imediata | Armazena mensagens |

---

## 🧠 Conceitos importantes para prova

- SNS usa pub/sub
- Envia mensagens para múltiplos destinos
- Usa tópicos
- Não armazena mensagens

---

## ⚠️ Pegadinhas comuns

- Achar que SNS é fila
- Esperar armazenamento de mensagens
- Confundir com SQS

---

## 🔁 Resumo rápido

- SNS = pub/sub
- Envia mensagens para vários destinos
- Não armazena mensagens

---

## 📌 Status de aprendizado

- [ ] Entendo o que é SNS
- [ ] Sei o que é um tópico
- [ ] Entendo pub/sub
- [ ] Sei diferença para SQS

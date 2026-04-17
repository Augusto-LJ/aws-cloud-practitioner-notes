# 📥 Amazon SQS (Simple Queue Service)

## 📌 O que é

O Amazon SQS é um serviço de **fila de mensagens** totalmente gerenciado.

Permite comunicação assíncrona entre sistemas.

---

## 🎯 Quando usar

- Processamento assíncrono
- Desacoplamento de serviços
- Filas de tarefas (jobs)
- Absorver picos de requisições

---

## ⚙️ Como funciona

- Um produtor envia mensagens para a fila
- Um consumidor processa essas mensagens
- Após o processamento, a mensagem é removida

---

## 📦 Tipos de fila

### ⚡ Standard Queue
- Alta performance
- Entrega **pelo menos uma vez**
- Pode haver duplicidade

---

### 📏 FIFO Queue
- Ordem garantida
- Sem duplicidade
- Menor throughput

---

## 🔑 Conceitos importantes

### ⏳ Visibility Timeout
- Tempo em que a mensagem fica invisível após ser consumida
- Evita processamento duplicado

---

### 🔁 Dead Letter Queue (DLQ)
- Armazena mensagens que falharam várias vezes
- Ajuda na análise de erros

---

## 🚀 Casos de uso

- Processamento de pedidos
- Filas de envio de e-mails
- Processamento de imagens
- Integração entre microsserviços

---

## 💰 Benefícios

- Alta escalabilidade
- Desacoplamento
- Confiabilidade

---

## ⚖️ Comparações importantes

### SQS vs SNS

| SQS | SNS |
|-----|-----|
| Fila | Pub/Sub |
| 1 consumidor | Múltiplos consumidores |
| Armazena mensagens | Não armazena |

---

## 🧠 Conceitos importantes para prova

- SQS é uma fila de mensagens
- Suporta Standard e FIFO
- Garante entrega (at least once)
- Permite DLQ

---

## ⚠️ Pegadinhas comuns

- Esperar ordem em fila Standard
- Ignorar duplicidade
- Não configurar DLQ

---

## 🔁 Resumo rápido

- SQS = fila
- Comunicação assíncrona
- Desacoplamento
- Alta escalabilidade

---

## 📌 Status de aprendizado

- [ ] Entendo o que é SQS
- [ ] Sei diferença entre Standard e FIFO
- [ ] Entendo Visibility Timeout
- [ ] Sei o que é DLQ

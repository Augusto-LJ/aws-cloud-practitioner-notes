# 📬 Conceitos de Mensageria

## 📌 O que é

Mensageria é um padrão de arquitetura que permite a **comunicação entre sistemas de forma assíncrona**.

Ela ajuda a desacoplar componentes, aumentando a escalabilidade e resiliência.

---

## 🎯 Quando usar

- Comunicação entre sistemas distribuídos
- Processamento assíncrono
- Redução de acoplamento entre serviços
- Absorver picos de carga

---

## ⚙️ Como funciona

- Um serviço envia uma mensagem
- Outro serviço consome essa mensagem
- Não é necessário que ambos estejam ativos ao mesmo tempo

---

## 📦 Conceitos importantes

### 📥 Fila (Queue)
- Mensagens são armazenadas até serem processadas
- Cada mensagem é consumida por **um único consumidor**

---

### 📣 Publicação/Assinatura (Pub/Sub)
- Uma mensagem é enviada para múltiplos consumidores
- Baseado em tópicos (topics)

---

### 🔄 Processamento assíncrono
- O produtor não espera resposta imediata
- A execução ocorre em segundo plano

---

### 🔗 Desacoplamento
- Serviços não dependem diretamente uns dos outros
- Facilita manutenção e escalabilidade

---

## ⚖️ Comparações importantes

### SQS vs SNS

| SQS | SNS |
|-----|-----|
| Fila (queue) | Pub/Sub |
| 1 consumidor | Múltiplos consumidores |
| Armazena mensagens | Não armazena (entrega imediata) |

---

## 🧠 Conceitos importantes para prova

- Mensageria permite comunicação assíncrona
- Reduz acoplamento entre serviços
- SQS = fila
- SNS = pub/sub

---

## ⚠️ Pegadinhas comuns

- Confundir fila com pub/sub
- Achar que SNS armazena mensagens
- Esquecer que SQS desacopla sistemas

---

## 🔁 Resumo rápido

- Mensageria = comunicação assíncrona
- Desacopla sistemas
- SQS → fila
- SNS → pub/sub

---

## 📌 Status de aprendizado

- [ ] Entendo o conceito de mensageria
- [ ] Sei diferença entre SQS e SNS
- [ ] Entendo processamento assíncrono

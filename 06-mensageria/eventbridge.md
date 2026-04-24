# ⚡ Amazon EventBridge

## 📌 O que é

O Amazon EventBridge é um serviço de **event bus** que permite integrar aplicações usando eventos.

Ele conecta serviços AWS e aplicações próprias de forma desacoplada.

---

## 🎯 Quando usar

- Arquiteturas orientadas a eventos
- Integração entre serviços AWS
- Automação baseada em eventos

---

## ⚙️ Como funciona

- Um serviço gera um evento
- O EventBridge recebe esse evento
- Regras determinam para onde o evento será enviado

---

## 📦 Conceitos importantes

### 🚌 Event Bus
- Canal por onde eventos trafegam

---

### 📜 Rules (Regras)
- Definem como eventos são filtrados e direcionados

---

### 🎯 Targets
- Destinos dos eventos
- Exemplos:
  - Lambda
  - SQS
  - SNS
  - Step Functions

---

## 🔍 Tipos de eventos

- Eventos de serviços AWS (ex: EC2, S3)
- Eventos customizados (aplicações próprias)
- Eventos de SaaS (ex: integrações externas)

---

## 🚀 Casos de uso

- Automação de processos
- Integração entre sistemas
- Arquiteturas event-driven

---

## 💰 Benefícios

- Desacoplamento
- Escalabilidade
- Flexibilidade

---

## ⚖️ Comparações importantes

### EventBridge vs SNS

| EventBridge | SNS |
|-------------|-----|
| Baseado em eventos | Pub/Sub simples |
| Filtragem avançada | Sem filtragem complexa |
| Regras | Tópicos |

---

### EventBridge vs SQS

| EventBridge | SQS |
|-------------|-----|
| Eventos | Fila |
| Roteamento inteligente | Armazenamento |

---

## 🧠 Conceitos importantes para prova

- EventBridge usa eventos
- Permite integração entre serviços
- Usa regras para roteamento
- Suporta eventos AWS e customizados

---

## ⚠️ Pegadinhas comuns

- Confundir com SNS
- Achar que armazena mensagens como SQS
- Ignorar regras de filtragem

---

## 🔁 Resumo rápido

- EventBridge = integração por eventos
- Usa regras
- Conecta serviços AWS
- Base de arquiteturas event-driven

---

## 📌 Status de aprendizado

- [ ] Entendo o que é EventBridge
- [ ] Sei diferença para SNS e SQS
- [ ] Entendo conceito de event bus
- [ ] Sei como funcionam regras

# ⚖️ SQS vs SNS

## 🔗 Referências

- [SQS](../../06-mensageria/sqs.md)
- [SNS](../../06-mensageria/sns.md)

---

## 📌 Diferença principal (resumo rápido)

- **SQS** → Fila (pull)
- **SNS** → Pub/Sub (push)

---

## ⚖️ Comparação direta

| SQS | SNS |
|-----|-----|
| Fila | Pub/Sub |
| Pull (consumidor busca) | Push (envia automaticamente) |
| Uma mensagem por consumidor | Uma mensagem para vários |
| Desacoplamento | Broadcast |

---

## 🎯 Quando usar cada um

### SQS
- Processamento assíncrono
- Desacoplamento de sistemas
- Garantir processamento de mensagens

---

### SNS
- Notificações em tempo real
- Enviar mensagem para múltiplos destinos
- Eventos (fan-out)

---

## 🧠 Pegadinhas de prova

- SQS não envia mensagem automaticamente
- SNS não armazena mensagens como fila
- SNS pode enviar para SQS

---

## 🔁 Resumo em 1 linha

- **SQS = fila (pull)**
- **SNS = notificação (push)**

# ⚖️ SQS vs EventBridge

## 🔗 Referências

- [SQS](../../06-mensageria/sqs.md)
- [EventBridge](../../06-mensageria/eventbridge.md)

---

## 📌 Diferença principal (resumo rápido)

- **SQS** → Fila de mensagens
- **EventBridge** → Roteador de eventos

---

## ⚖️ Comparação direta

| SQS | EventBridge |
|-----|-------------|
| Fila | Event bus |
| Armazena mensagens | Roteia eventos |
| Consumidor faz pull | Push baseado em regras |
| Processamento | Integração |

---

## 🎯 Quando usar cada um

### SQS
- Processar mensagens
- Garantir entrega
- Desacoplar sistemas

---

### EventBridge
- Integração entre serviços
- Arquitetura orientada a eventos
- Roteamento inteligente

---

## 🧠 Pegadinhas de prova

- SQS guarda mensagens
- EventBridge não é fila
- EventBridge usa regras para roteamento

---

## 🔁 Resumo em 1 linha

- **SQS = fila**
- **EventBridge = roteador de eventos**

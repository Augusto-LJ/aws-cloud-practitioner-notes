# ⚖️ SNS vs EventBridge

## 🔗 Referências

- [SNS](../../06-mensageria/sns.md)
- [EventBridge](../../06-mensageria/eventbridge.md)

---

## 📌 Diferença principal (resumo rápido)

- **SNS** → Pub/Sub simples
- **EventBridge** → Event bus com regras

---

## ⚖️ Comparação direta

| SNS | EventBridge |
|-----|-------------|
| Pub/Sub simples | Event-driven avançado |
| Push | Baseado em regras |
| Menos filtragem | Filtragem avançada |
| Mais simples | Mais flexível |

---

## 🎯 Quando usar cada um

### SNS
- Notificações simples
- Fan-out básico
- Baixa complexidade

---

### EventBridge
- Arquiteturas event-driven
- Integração entre serviços
- Filtragem e roteamento avançado

---

## 🧠 Pegadinhas de prova

- EventBridge é mais inteligente (regras)
- SNS é mais simples
- EventBridge não é apenas notificação

---

## 🔁 Resumo em 1 linha

- **SNS = simples**
- **EventBridge = inteligente**

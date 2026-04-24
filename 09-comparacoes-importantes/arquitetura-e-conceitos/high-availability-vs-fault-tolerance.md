# ⚖️ Alta Disponibilidade vs Tolerância a Falhas

## 📌 Diferença principal (resumo rápido)

- **Alta disponibilidade** → minimizar downtime
- **Tolerância a falhas** → continuar funcionando mesmo com falha

---

## ⚖️ Comparação direta

| Alta Disponibilidade | Tolerância a Falhas |
|---------------------|---------------------|
| Reduz impacto | Evita impacto |
| Pode ter pequena interrupção | Sem interrupção |
| Mais simples | Mais complexo |

---

## 🎯 Quando usar cada um

### Alta disponibilidade
- Aplicações comuns
- Sistemas web
- Custos moderados

---

### Tolerância a falhas
- Sistemas críticos
- Bancos, finanças
- Missão crítica

---

## 🧠 Pegadinhas de prova

- HA pode ter downtime pequeno
- Fault tolerance = zero downtime (idealmente)
- Fault tolerance é mais caro

---

## 🔁 Resumo em 1 linha

- **Alta disponibilidade = quase sempre online**
- **Tolerância a falhas = sempre online**

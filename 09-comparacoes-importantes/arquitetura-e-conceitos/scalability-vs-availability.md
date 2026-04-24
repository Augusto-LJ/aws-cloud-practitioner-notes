# ⚖️ Escalabilidade vs Alta Disponibilidade

## 🔗 Referências

- [Auto Scaling](../../04-escalabilidade-e-alta-disponibilidade/amazon-ec2-autoscaling.md)
- [ELB](../../04-escalabilidade-e-alta-disponibilidade/elb.md)

---

## 📌 Diferença principal (resumo rápido)

- **Escalabilidade** → lidar com aumento de carga
- **Alta disponibilidade** → evitar indisponibilidade

---

## ⚖️ Comparação direta

| Escalabilidade | Alta Disponibilidade |
|---------------|----------------------|
| Aumenta recursos | Evita falhas |
| Crescimento | Resiliência |
| Performance | Continuidade |

---

## 🎯 Quando usar cada um

### Escalabilidade
- Aumento de usuários
- Picos de acesso
- Crescimento da aplicação

---

### Alta disponibilidade
- Evitar downtime
- Sistemas críticos
- Tolerância a falhas

---

## 🧠 Pegadinhas de prova

- Escalabilidade ≠ disponibilidade
- Sistema pode escalar e ainda cair
- Alta disponibilidade não significa escalar automaticamente

---

## 🔁 Resumo em 1 linha

- **Escalar = crescer**
- **Alta disponibilidade = não cair**

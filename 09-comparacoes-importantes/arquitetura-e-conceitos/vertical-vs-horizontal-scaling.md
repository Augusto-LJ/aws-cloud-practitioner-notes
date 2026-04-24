# ⚖️ Escalabilidade Vertical vs Horizontal

## 🔗 Referências

- [Auto Scaling](../../04-escalabilidade-e-alta-disponibilidade/amazon-ec2-autoscaling.md)

---

## 📌 Diferença principal (resumo rápido)

- **Vertical** → aumentar capacidade da máquina
- **Horizontal** → adicionar mais máquinas

---

## ⚖️ Comparação direta

| Vertical | Horizontal |
|----------|-----------|
| Scale up | Scale out |
| Mais CPU/RAM | Mais instâncias |
| Limitado | Altamente escalável |
| Mais simples | Mais resiliente |

---

## 🎯 Quando usar cada um

### Vertical
- Aplicações simples
- Baixa escala
- Banco de dados pequenos

---

### Horizontal
- Alta escala
- Aplicações distribuídas
- Cloud (AWS)

---

## 🧠 Pegadinhas de prova

- Vertical tem limite físico
- Horizontal é base da nuvem
- Auto Scaling usa horizontal

---

## 🔁 Resumo em 1 linha

- **Vertical = máquina maior**
- **Horizontal = mais máquinas**

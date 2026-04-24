# ⚖️ Auto Scaling vs ELB

## 🔗 Referências

- [Auto Scaling](../04-escalabilidade-e-alta-disponibilidade/amazon-ec2-autoscaling.md)
- [ELB](../04-escalabilidade-e-alta-disponibilidade/elb.md)

---

## 📌 Diferença principal (resumo rápido)

- **Auto Scaling** → Ajusta quantidade de instâncias
- **ELB** → Distribui tráfego entre instâncias

---

## ⚖️ Comparação direta

| Auto Scaling | ELB |
|--------------|-----|
| Escala recursos | Balanceia tráfego |
| Cria/remove instâncias | Distribui requisições |
| Focado em capacidade | Focado em disponibilidade |
| Atua com demanda | Atua com tráfego |

---

## 🎯 Quando usar cada um

### Auto Scaling
- Ajustar capacidade automaticamente
- Evitar sobrecarga ou ociosidade

---

### ELB
- Distribuir requisições
- Aumentar disponibilidade

---

## 🧠 Pegadinhas de prova

- ELB não escala instâncias
- Auto Scaling não distribui tráfego
- Geralmente usados juntos

---

## 🔁 Resumo em 1 linha

- **Auto Scaling escala**
- **ELB distribui**

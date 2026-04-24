# ⚖️ S3 Standard-IA vs One Zone-IA

## 🔗 Referências

- [S3](../../01-principais-servicos/armazenamento/s3.md)

---

## 📌 Diferença principal (resumo rápido)

- **Standard-IA** → Multi-AZ
- **One Zone-IA** → Uma única AZ

---

## ⚖️ Comparação direta

| Standard-IA | One Zone-IA |
|-------------|------------|
| Multi-AZ | Single-AZ |
| Mais seguro | Menos resiliente |
| Mais caro | Mais barato |
| Alta durabilidade | Menor disponibilidade |

---

## 🎯 Quando usar cada um

### Standard-IA
- Dados importantes
- Backup com alta disponibilidade

---

### One Zone-IA
- Dados recriáveis
- Backup secundário
- Dados menos críticos

---

## 🧠 Pegadinhas de prova

- One Zone-IA pode perder dados se AZ falhar
- Standard-IA é mais resiliente
- Ambos são para acesso infrequente

---

## 🔁 Resumo em 1 linha

- **Standard-IA = seguro**
- **One Zone-IA = mais barato, menos resiliente**

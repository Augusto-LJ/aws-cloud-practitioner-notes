# ⚖️ Redshift vs Athena

## 🔗 Referências

- [Redshift](../../01-principais-servicos/big-data/redshift.md)

---

## 📌 Diferença principal (resumo rápido)

- **Redshift** → Data warehouse provisionado
- **Athena** → Query direto no S3 (serverless)

---

## ⚖️ Comparação direta

| Redshift | Athena |
|----------|--------|
| Provisionado | Serverless |
| Armazena dados | Consulta no S3 |
| Mais rápido (grande escala) | Mais flexível |
| Mais caro (fixo) | Paga por consulta |

---

## 🎯 Quando usar cada um

### Redshift
- Data warehouse estruturado
- Alto volume constante

---

### Athena
- Consultas ocasionais
- Dados no S3
- Sem infraestrutura

---

## 🧠 Pegadinhas de prova

- Athena não armazena dados
- Redshift precisa de cluster
- Athena é pay-per-query

---

## 🔁 Resumo em 1 linha

- **Redshift = warehouse**
- **Athena = query no S3**

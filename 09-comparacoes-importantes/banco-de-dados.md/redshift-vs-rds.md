# ⚖️ Redshift vs RDS

## 🔗 Referências

- [Redshift](../../01-principais-servicos/big-data/redshift.md)
- [RDS](../../01-principais-servicos/banco-de-dados/rds.md)

---

## 📌 Diferença principal (resumo rápido)

- **RDS** → OLTP (transacional)
- **Redshift** → OLAP (analítico)

---

## ⚖️ Comparação direta

| RDS | Redshift |
|-----|----------|
| Transacional | Analítico |
| Dados operacionais | Data warehouse |
| Menor escala | Grandes volumes |
| Baixa latência | Consultas complexas |

---

## 🎯 Quando usar cada um

### RDS
- Aplicações do dia a dia
- CRUD
- Sistemas operacionais

---

### Redshift
- BI e analytics
- Big Data
- Relatórios complexos

---

## 🧠 Pegadinhas de prova

- Redshift não é para aplicações transacionais
- RDS não é ideal para analytics pesado
- OLTP vs OLAP é chave

---

## 🔁 Resumo em 1 linha

- **RDS = operação**
- **Redshift = análise**

# ⚖️ RDS vs DynamoDB

## 🔗 Referências

- [RDS](../../01-principais-servicos/banco-de-dados/rds.md)
- [DynamoDB](../../01-principais-servicos/banco-de-dados/dynamodb.md)

---

## 📌 Diferença principal (resumo rápido)

- **RDS** → Banco relacional (SQL)
- **DynamoDB** → Banco NoSQL (chave-valor)

---

## ⚖️ Comparação direta

| RDS | DynamoDB |
|-----|----------|
| Relacional (SQL) | NoSQL |
| Schema fixo | Schema flexível |
| Relacionamentos | Sem joins |
| Escalabilidade limitada | Escala automaticamente |
| Mais complexo | Alta performance |

---

## 🎯 Quando usar cada um

### RDS
- Sistemas com relacionamentos
- Aplicações tradicionais
- Uso de SQL

---

### DynamoDB
- Alta escala
- Baixa latência
- Aplicações serverless

---

## 🧠 Pegadinhas de prova

- DynamoDB não usa SQL tradicional
- RDS não escala automaticamente como DynamoDB
- DynamoDB não é ideal para joins

---

## 🔁 Resumo em 1 linha

- **RDS = relacional**
- **DynamoDB = NoSQL escalável**

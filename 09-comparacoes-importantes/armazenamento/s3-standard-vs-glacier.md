# ⚖️ S3 Standard vs Glacier

## 🔗 Referências

- [S3](../../01-principais-servicos/armazenamento/s3.md)

---

## 📌 Diferença principal (resumo rápido)

- **Standard** → Acesso frequente
- **Glacier** → Arquivamento (acesso raro)

---

## ⚖️ Comparação direta

| S3 Standard | Glacier |
|-------------|--------|
| Acesso imediato | Acesso lento |
| Mais caro | Muito mais barato |
| Uso frequente | Uso raro |
| Alta disponibilidade | Foco em custo |

---

## 🎯 Quando usar cada um

### Standard
- Aplicações ativas
- Sites e APIs
- Conteúdo frequente

---

### Glacier
- Arquivamento
- Backups de longo prazo
- Dados raramente acessados

---

## 🧠 Pegadinhas de prova

- Glacier não é para acesso rápido
- Standard é mais caro por ser rápido
- Glacier tem tempo de recuperação

---

## 🔁 Resumo em 1 linha

- **Standard = rápido**
- **Glacier = barato**

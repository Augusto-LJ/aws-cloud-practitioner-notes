# ⚖️ S3 vs EBS

## 🔗 Referências

- [S3](../../01-principais-servicos/armazenamento/s3.md)
- [EBS](../../01-principais-servicos/armazenamento/ebs.md)

---

## 📌 Diferença principal (resumo rápido)

- **S3** → Armazenamento de objetos
- **EBS** → Armazenamento em bloco (disco de EC2)

---

## ⚖️ Comparação direta

| S3 | EBS |
|----|-----|
| Armazenamento de objetos | Armazenamento em bloco |
| Acesso via HTTP/API | Acesso como disco |
| Altamente escalável | Limitado a uma instância |
| Não precisa de EC2 | Precisa de EC2 |
| Ideal para arquivos | Ideal para sistema operacional |

---

## 🎯 Quando usar cada um

### S3
- Armazenar arquivos (imagens, vídeos, backups)
- Data lakes
- Conteúdo estático

---

### EBS
- Disco de instância EC2
- Banco de dados
- Sistemas operacionais

---

## 🧠 Pegadinhas de prova

- S3 não é um disco
- EBS não é compartilhado entre várias instâncias (por padrão)
- S3 não precisa de EC2

---

## 🔁 Resumo em 1 linha

- **S3 = arquivos**
- **EBS = disco de servidor**

# ⚖️ S3 vs EFS

## 🔗 Referências

- [S3](../../01-principais-servicos/armazenamento/s3.md)
- [EFS](../../01-principais-servicos/armazenamento/efs.md)

---

## 📌 Diferença principal (resumo rápido)

- **S3** → Armazenamento de objetos
- **EFS** → Sistema de arquivos (file system)

---

## ⚖️ Comparação direta

| S3 | EFS |
|----|-----|
| Objetos (arquivos via API) | Sistema de arquivos (NFS) |
| Não monta como disco | Montável em EC2 |
| Escala praticamente ilimitado | Escala automaticamente |
| Acesso via HTTP | Acesso via rede |
| Mais barato | Mais caro |

---

## 🎯 Quando usar cada um

### S3
- Armazenamento de arquivos
- Conteúdo estático
- Backup

---

### EFS
- Compartilhamento de arquivos entre EC2
- Aplicações que precisam de filesystem

---

## 🧠 Pegadinhas de prova

- EFS pode ser montado como disco
- S3 não suporta filesystem tradicional
- EFS é compartilhado (multi instância)

---

## 🔁 Resumo em 1 linha

- **S3 = armazenamento de objetos**
- **EFS = filesystem compartilhado**

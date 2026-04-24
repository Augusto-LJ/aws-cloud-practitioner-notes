# ⚖️ EBS vs EFS

## 🔗 Referências

- [EBS](../../01-principais-servicos/armazenamento/ebs.md)
- [EFS](../../01-principais-servicos/armazenamento/efs.md)

---

## 📌 Diferença principal (resumo rápido)

- **EBS** → Disco para uma instância
- **EFS** → Sistema de arquivos compartilhado

---

## ⚖️ Comparação direta

| EBS | EFS |
|-----|-----|
| Armazenamento em bloco | Sistema de arquivos |
| Uma instância (por padrão) | Várias instâncias |
| Alta performance | Compartilhado |
| Mais barato | Mais caro |
| Precisa anexar | Montado via rede |

---

## 🎯 Quando usar cada um

### EBS
- Banco de dados
- Sistema operacional
- Alta performance

---

### EFS
- Compartilhamento entre instâncias
- Aplicações distribuídas

---

## 🧠 Pegadinhas de prova

- EBS não é compartilhado (por padrão)
- EFS é multi-AZ
- EFS é mais caro

---

## 🔁 Resumo em 1 linha

- **EBS = disco individual**
- **EFS = disco compartilhado**

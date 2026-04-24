# ⚖️ IAM vs Organizations

## 🔗 Referências

- [IAM](../../02-seguranca/iam.md)
- [AWS Organizations](../../02-seguranca/aws-organizations.md)

---

## 📌 Diferença principal (resumo rápido)

- **IAM** → Controle de acesso dentro de uma conta
- **Organizations** → Gerenciamento de múltiplas contas

---

## ⚖️ Comparação direta

| IAM | Organizations |
|-----|--------------|
| Atua em uma conta | Atua em várias contas |
| Controle de usuários e permissões | Organização de contas |
| Usuários, grupos e roles | Contas e políticas globais |
| Segurança operacional | Governança |

---

## 🎯 Quando usar cada um

### IAM
- Gerenciar usuários
- Definir permissões
- Controle de acesso

---

### Organizations
- Gerenciar várias contas
- Centralizar faturamento
- Aplicar políticas globais

---

## 🧠 Pegadinhas de prova

- IAM não gerencia múltiplas contas
- Organizations não substitui IAM
- Organizations usa SCPs (Service Control Policies)

---

## 🔁 Resumo em 1 linha

- **IAM = controle de acesso**
- **Organizations = governança multi-conta**

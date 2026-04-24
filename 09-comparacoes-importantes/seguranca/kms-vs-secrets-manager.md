# ⚖️ KMS vs Secrets Manager

## 🔗 Referências

- [KMS](../../02-seguranca/kms.md)

---

## 📌 Diferença principal (resumo rápido)

- **KMS** → Gerencia chaves de criptografia
- **Secrets Manager** → Armazena e gerencia segredos

---

## ⚖️ Comparação direta

| KMS | Secrets Manager |
|-----|----------------|
| Gerencia chaves | Gerencia segredos |
| Criptografia | Armazenamento seguro |
| Base para outros serviços | Uso direto em aplicações |
| Não armazena credenciais | Armazena credenciais |

---

## 🎯 Quando usar cada um

### KMS
- Criptografar dados
- Gerenciar chaves
- Integração com outros serviços

---

### Secrets Manager
- Armazenar senhas
- Armazenar tokens e APIs
- Rotação automática de segredos

---

## 🧠 Pegadinhas de prova

- KMS não é para guardar senhas
- Secrets Manager pode usar KMS por trás
- KMS é base de criptografia

---

## 🔁 Resumo em 1 linha

- **KMS = chaves**
- **Secrets Manager = segredos**

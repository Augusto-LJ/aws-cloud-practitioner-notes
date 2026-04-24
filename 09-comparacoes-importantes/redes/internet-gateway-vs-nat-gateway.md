# ⚖️ Internet Gateway vs NAT Gateway

## 🔗 Referências

- [VPC](../../01-principais-servicos/redes/vpc.md)

---

## 📌 Diferença principal (resumo rápido)

- **Internet Gateway** → Permite acesso direto à internet
- **NAT Gateway** → Permite saída para internet sem entrada

---

## ⚖️ Comparação direta

| Internet Gateway | NAT Gateway |
|------------------|------------|
| Entrada e saída | Apenas saída |
| Usado em sub-rede pública | Usado em sub-rede privada |
| Conexão direta com internet | Protege recursos internos |
| Público | Privado |

---

## 🎯 Quando usar cada um

### Internet Gateway
- Recursos públicos
- Acesso direto à internet

---

### NAT Gateway
- Instâncias privadas acessarem internet
- Segurança (sem acesso externo direto)

---

## 🧠 Pegadinhas de prova

- NAT não permite entrada
- Internet Gateway é necessário para sub-rede pública
- NAT Gateway fica em sub-rede pública

---

## 🔁 Resumo em 1 linha

- **IGW = acesso direto**
- **NAT = saída segura**

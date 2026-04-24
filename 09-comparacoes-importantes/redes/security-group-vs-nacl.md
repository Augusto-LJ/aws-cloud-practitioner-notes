# ⚖️ Security Group vs NACL

## 🔗 Referências

- [VPC](../../01-principais-servicos/redes/vpc/vpc.md)
- [Security group](../../01-principais-servicos/redes/vpc/grupos-de-seguranca.md)
- [NACL](../../01-principais-servicos/redes/vpc/nacl.md)

---

## 📌 Diferença principal (resumo rápido)

- **Security Group** → Firewall no nível da instância (stateful)
- **NACL** → Firewall no nível da sub-rede (stateless)

---

## ⚖️ Comparação direta

| Security Group | NACL |
|----------------|------|
| Nível da instância | Nível da sub-rede |
| Stateful | Stateless |
| Permite regras de allow apenas | Allow e deny |
| Mais simples | Mais granular |
| Avalia apenas entrada (resposta liberada automaticamente) | Avalia entrada e saída |

---

## 🎯 Quando usar cada um

### Security Group
- Controle direto nas instâncias
- Regras simples
- Uso mais comum

---

### NACL
- Controle adicional na sub-rede
- Bloqueios explícitos (deny)
- Segurança mais granular

---

## 🧠 Pegadinhas de prova

- Security Group é **stateful**
- NACL é **stateless**
- Security Group não tem regra de deny
- NACL precisa liberar entrada **e saída**

---

## 🔁 Resumo em 1 linha

- **Security Group = firewall da instância**
- **NACL = firewall da sub-rede**

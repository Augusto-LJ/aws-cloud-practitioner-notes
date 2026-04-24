# ⚖️ EKS vs Fargate

## 🔗 Referências

- [EKS](../01-principais-servicos/computacao/eks.md)
- [Fargate](../01-principais-servicos/computacao/fargate.md)

---

## 📌 Diferença principal (resumo rápido)

- **EKS** → Orquestra containers com Kubernetes
- **Fargate** → Executa containers sem servidor

---

## ⚖️ Comparação direta

| EKS | Fargate |
|-----|---------|
| Orquestrador (Kubernetes) | Execução serverless |
| Gerencia cluster | Não gerencia cluster |
| Mais complexo | Mais simples |
| Pode usar Fargate | Integrado ao EKS |

---

## 🎯 Quando usar cada um

### EKS
- Precisa de Kubernetes
- Alta complexidade

---

### Fargate
- Quer simplificar execução
- Evitar servidores

---

## 🧠 Pegadinhas de prova

- Fargate não substitui EKS
- EKS define **como orquestrar**
- Fargate define **como executar**

---

## 🔁 Resumo em 1 linha

- **EKS orquestra**
- **Fargate executa**

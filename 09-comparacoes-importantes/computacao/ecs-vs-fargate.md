# ⚖️ ECS vs Fargate

## 🔗 Referências

- [ECS](../../01-principais-servicos/computacao/ecs.md)
- [Fargate](../../01-principais-servicos/computacao/fargate.md)

---

## 📌 Diferença principal (resumo rápido)

- **ECS** → Orquestra containers
- **Fargate** → Executa containers sem servidor

---

## ⚖️ Comparação direta

| ECS | Fargate |
|-----|---------|
| Orquestrador | Motor de execução |
| Precisa gerenciar EC2 (opcional) | Serverless |
| Mais controle | Menos controle |
| Pode usar Fargate | Integrado ao ECS/EKS |

---

## 🎯 Quando usar cada um

### ECS
- Precisa controlar infraestrutura
- Quer usar EC2

---

### Fargate
- Quer evitar gerenciar servidores
- Execução simples de containers

---

## 🧠 Pegadinhas de prova

- Fargate **não substitui ECS**
- Fargate é usado **junto com ECS ou EKS**
- ECS pode rodar com EC2 ou Fargate

---

## 🔁 Resumo em 1 linha

- **ECS gerencia**
- **Fargate executa**

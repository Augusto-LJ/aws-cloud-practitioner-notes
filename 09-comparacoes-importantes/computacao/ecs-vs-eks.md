# ⚖️ ECS vs EKS

## 🔗 Referências

- [ECS](../01-principais-servicos/computacao/ecs.md)
- [EKS](../01-principais-servicos/computacao/eks.md)

---

## 📌 Diferença principal (resumo rápido)

- **ECS** → Orquestração de containers nativa da AWS
- **EKS** → Kubernetes gerenciado pela AWS

---

## ⚖️ Comparação direta

| ECS | EKS |
|-----|-----|
| Serviço próprio da AWS | Kubernetes (padrão de mercado) |
| Mais simples | Mais complexo |
| Menos flexível | Altamente flexível |
| Integração nativa com AWS | Portável (multi-cloud) |

---

## 🎯 Quando usar cada um

### ECS
- Simplicidade
- Projetos AWS-centric
- Menor curva de aprendizado

---

### EKS
- Já usa Kubernetes
- Precisa de portabilidade
- Ambientes complexos

---

## 🧠 Pegadinhas de prova

- EKS = Kubernetes (sempre associe)
- ECS não usa Kubernetes
- ECS é mais simples → comum em cenários iniciais

---

## 🔁 Resumo em 1 linha

- **ECS = simples e nativo AWS**
- **EKS = Kubernetes gerenciado**

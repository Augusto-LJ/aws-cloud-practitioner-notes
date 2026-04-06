# ☸️ Amazon EKS (Elastic Kubernetes Service)

## 📌 O que é

O Amazon EKS é um serviço gerenciado que permite executar **Kubernetes na AWS**.

Ele facilita a criação e gerenciamento de clusters Kubernetes.

---

## 🎯 Quando usar

- Executar aplicações com Kubernetes
- Padronizar infraestrutura multi-cloud
- Ter maior controle sobre containers

---

## ⚙️ Como funciona

- A AWS gerencia o plano de controle (control plane)
- Você gerencia os workers (ou usa Fargate)
- Aplicações são executadas em pods Kubernetes

---

## 📦 Conceitos importantes

### ☸️ Cluster Kubernetes
- Conjunto de máquinas (nodes)
- Executa aplicações containerizadas

---

### 📦 Pod
- Unidade básica de execução
- Pode conter um ou mais containers

---

### 🖥️ Node
- Máquina (EC2 ou Fargate) que executa pods

---

### 🎯 Control Plane
- Gerenciado pela AWS
- Responsável por:
  - Agendamento
  - Gerenciamento do cluster

---

## 🚀 Modos de execução

### 🖥️ EC2
- Nodes gerenciados pelo usuário

---

### ⚡ Fargate
- Execução serverless de pods

---

## 🚀 Casos de uso

- Microsserviços complexos
- Ambientes multi-cloud
- Aplicações que já usam Kubernetes

---

## 💰 Benefícios

- Kubernetes gerenciado
- Alta disponibilidade
- Portabilidade
- Flexibilidade

---

## ⚖️ Comparações importantes

### EKS vs ECS

| EKS | ECS |
|-----|-----|
| Kubernetes | Proprietário AWS |
| Mais complexo | Mais simples |
| Mais flexível | Mais integrado |

---

### EKS vs Kubernetes self-managed

| EKS | Self-managed |
|-----|-------------|
| AWS gerencia control plane | Você gerencia tudo |
| Mais simples | Mais complexo |

---

## 🧠 Conceitos importantes para prova

- EKS roda Kubernetes
- AWS gerencia control plane
- Pode usar EC2 ou Fargate
- Mais complexo que ECS

---

## ⚠️ Pegadinhas comuns

- Confundir EKS com ECS
- Achar que EKS elimina Kubernetes (na verdade usa Kubernetes)
- Subestimar complexidade

---

## 🔁 Resumo rápido

- EKS = Kubernetes na AWS
- Mais flexível, porém mais complexo
- Indicado para quem já usa Kubernetes

---

## 📌 Status de aprendizado

- [ ] Entendo o que é EKS
- [ ] Sei o que é Kubernetes
- [ ] Entendo diferença para ECS
- [ ] Sei quando usar EKS

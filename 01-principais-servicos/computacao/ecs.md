# 🐳 Amazon ECS (Elastic Container Service)

## 📌 O que é

O Amazon ECS é um serviço de **orquestração de containers** totalmente gerenciado pela AWS.

Ele permite executar e gerenciar containers Docker de forma escalável.

---

## 🎯 Quando usar

- Executar aplicações em containers
- Substituir máquinas virtuais por containers
- Simplificar gerenciamento de infraestrutura

---

## ⚙️ Como funciona

- Você define tarefas (tasks) com containers
- O ECS executa essas tarefas em um cluster
- Pode escalar automaticamente conforme demanda

---

## 📦 Conceitos importantes

### 🧩 Cluster
- Conjunto de recursos computacionais
- Onde os containers são executados

---

### 📦 Task Definition
- Define como o container será executado
- Inclui:
  - Imagem Docker
  - CPU e memória
  - Configurações

---

### ▶️ Task
- Instância em execução de uma Task Definition

---

### 🔄 Service
- Mantém tarefas rodando continuamente
- Permite escalabilidade automática

---

## 🚀 Modos de execução

### 🖥️ EC2 Launch Type
- Containers executados em instâncias EC2
- Mais controle
- Mais gerenciamento

---

### ⚡ Fargate Launch Type
- Serverless para containers
- AWS gerencia infraestrutura
- Mais simples

---

## 🚀 Casos de uso

- Microsserviços
- APIs em containers
- Processamento em lote

---

## 💰 Benefícios

- Totalmente gerenciado
- Integração com AWS
- Escalabilidade automática
- Suporte a Fargate (serverless)

---

## ⚖️ Comparações importantes

### ECS vs EKS

| ECS | EKS |
|-----|-----|
| Proprietário AWS | Kubernetes |
| Mais simples | Mais flexível |
| Menos complexidade | Mais controle |

---

### ECS EC2 vs Fargate

| EC2 | Fargate |
|-----|---------|
| Gerencia servidores | Serverless |
| Mais controle | Mais simples |

---

## 🧠 Conceitos importantes para prova

- ECS é orquestrador de containers
- Suporta EC2 e Fargate
- Task Definition define containers
- Service mantém tarefas ativas

---

## ⚠️ Pegadinhas comuns

- Confundir ECS com EKS
- Achar que ECS usa Kubernetes (não usa)
- Não entender diferença EC2 vs Fargate

---

## 🔁 Resumo rápido

- ECS = containers gerenciados pela AWS
- Simples e integrado
- Pode ser serverless (Fargate)

---

## 📌 Status de aprendizado

- [ ] Entendo o que é ECS
- [ ] Sei diferença entre EC2 e Fargate
- [ ] Entendo Task e Service
- [ ] Sei diferença para EKS

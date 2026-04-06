# ⚡ AWS Fargate

## 📌 O que é

O AWS Fargate é um serviço que permite executar **containers sem gerenciar servidores**.

Ele é um modelo **serverless para containers**, usado com ECS e EKS.

---

## 🎯 Quando usar

- Executar containers sem gerenciar infraestrutura
- Simplificar deploy de aplicações containerizadas
- Reduzir complexidade operacional

---

## ⚙️ Como funciona

- Você define containers (ECS ou EKS)
- Escolhe Fargate como modo de execução
- A AWS provisiona automaticamente os recursos necessários

---

## 📦 Conceitos importantes

### 🚫 Sem gerenciamento de servidores
- Não precisa criar ou gerenciar EC2
- AWS cuida de:
  - Provisionamento
  - Escalabilidade
  - Infraestrutura

---

### 📏 Definição de recursos
- Você define:
  - CPU
  - Memória
- Paga apenas pelo que usar

---

## 🔗 Integrações

- ECS → execução de tasks
- EKS → execução de pods
- CloudWatch → monitoramento
- IAM → controle de acesso

---

## 🚀 Casos de uso

- Microsserviços
- APIs em containers
- Processamento sob demanda
- Aplicações com carga variável

---

## 💰 Benefícios

- Serverless
- Sem gerenciamento de servidores
- Escalabilidade automática
- Cobrança por uso

---

## ⚖️ Comparações importantes

### Fargate vs EC2

| Fargate | EC2 |
|---------|-----|
| Serverless | Gerenciado pelo usuário |
| Sem servidores | Requer gerenciamento |
| Mais simples | Mais controle |

---

### Fargate vs Lambda

| Fargate | Lambda |
|---------|--------|
| Containers | Funções |
| Execuções mais longas | Execuções curtas |
| Mais flexível | Mais simples |

---

### Fargate + ECS vs ECS com EC2

| Fargate | EC2 |
|---------|-----|
| Sem infraestrutura | Infra gerenciada pelo usuário |
| Menos controle | Mais controle |

---

## 🧠 Conceitos importantes para prova

- Fargate é serverless para containers
- Funciona com ECS e EKS
- Não precisa gerenciar EC2
- Cobrança baseada em CPU e memória

---

## ⚠️ Pegadinhas comuns

- Achar que Fargate é um orquestrador
- Confundir com ECS ou EKS
- Pensar que elimina containers (na verdade executa containers)
- Ignorar custo (pode ser mais caro que EC2)

---

## 🔁 Resumo rápido

- Fargate = containers sem servidor
- Usado com ECS/EKS
- Simples e escalável
- Pay-as-you-go

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Fargate
- [ ] Sei diferença para EC2
- [ ] Entendo relação com ECS/EKS
- [ ] Sei quando usar

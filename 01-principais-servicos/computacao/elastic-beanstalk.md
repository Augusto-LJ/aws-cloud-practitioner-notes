# 🌱 AWS Elastic Beanstalk

## 📌 O que é

O AWS Elastic Beanstalk é um serviço que permite fazer **deploy de aplicações sem gerenciar infraestrutura**.

Você envia o código e a AWS cuida de:

- Provisionamento
- Escalabilidade
- Balanceamento de carga
- Monitoramento

---

## 🎯 Quando usar

- Deploy rápido de aplicações web
- Não querer gerenciar infraestrutura
- Focar apenas no código

---

## ⚙️ Como funciona

1. Você envia o código da aplicação
2. O Beanstalk:
   - Cria infraestrutura (EC2, ELB, Auto Scaling, etc.)
   - Configura ambiente
3. Sua aplicação fica disponível automaticamente

---

## 📦 Plataformas suportadas

- .NET
- Java
- Node.js
- Python
- PHP
- Docker

---

## 🧱 O que o Beanstalk usa por baixo

- EC2
- Auto Scaling
- Elastic Load Balancer
- CloudWatch

👉 Tudo gerenciado automaticamente

---

## 🚀 Casos de uso

- APIs
- Aplicações web
- MVPs
- Projetos rápidos

---

## 💰 Benefícios

- Fácil de usar
- Deploy rápido
- Gerenciamento automático
- Escalabilidade integrada

---

## ⚖️ Comparações importantes

### Beanstalk vs EC2

| Beanstalk | EC2 |
|----------|-----|
| Gerenciado | Manual |
| Deploy simples | Configuração completa |
| Menos controle | Mais controle |

---

### Beanstalk vs ECS

| Beanstalk | ECS |
|----------|-----|
| Foco em aplicações | Foco em containers |
| Mais simples | Mais flexível |

---

### Beanstalk vs Lambda

| Beanstalk | Lambda |
|----------|--------|
| Aplicações completas | Funções |
| Execução contínua | Event-driven |

---

## 🧠 Conceitos importantes para prova

- Beanstalk é PaaS
- Você envia código, não infraestrutura
- AWS gerencia recursos automaticamente
- Usa vários serviços por baixo

---

## ⚠️ Pegadinhas comuns

- Confundir com CloudFormation
- Achar que não usa EC2 (usa sim, mas abstraído)
- Pensar que é serverless (não é totalmente)

---

## 🔁 Resumo rápido

- Beanstalk = deploy fácil de aplicações
- Não precisa gerenciar infraestrutura
- Ideal para quem quer simplicidade

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Beanstalk
- [ ] Sei quando usar
- [ ] Entendo diferença para EC2
- [ ] Sei diferença para CloudFormation

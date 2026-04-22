# 🚚 Estratégias de Migração para a AWS (6 Rs)

## 📌 O que é

As estratégias de migração da AWS são um conjunto de abordagens conhecidas como **6 Rs**, usadas para mover aplicações para a nuvem.

Cada estratégia define **como uma aplicação será tratada durante a migração**.

---

## 🎯 Quando usar

- Migrar aplicações para a AWS
- Modernizar sistemas legados
- Reduzir custos ou melhorar performance
- Planejar transformação digital

---

## 📦 As 6 estratégias (6 Rs)

### 🔁 Rehost / Lift-and-Shift (Redefinir hospedagem)
- Move a aplicação **sem alterações**
- Ex: servidor on-premises → EC2

📌 Quando usar:
- Migração rápida
- Pouco tempo disponível

---

### 🔧 Replatform / Lift-tinker-and-shift (Redefinir plataforma)
- Pequenas otimizações
- Sem alterar arquitetura principal

📌 Exemplo:
- Banco local → Amazon RDS

📌 Quando usar:
- Melhorar performance sem grande esforço

---

### 🧱 Repurchase / Drop-and-shop (Recomprar)
- Substituir aplicação por outra (geralmente SaaS)

📌 Exemplo:
- Sistema interno → Salesforce

📌 Quando usar:
- Aplicação antiga ou limitada

---

### 🛠️ Refactor / Re-architect (Refatorar/Rearquitetura)
- Reescrever aplicação para cloud-native

📌 Exemplo:
- Monolito → microservices + Lambda

📌 Quando usar:
- Alta escalabilidade
- Modernização completa
- Quando há necessidade de adicionar recursos, scaling ou desempenho

---

### 📦 Retain (Reter)
- Manter aplicação **on-premises**.
- Não migrar para AWS apenas o que faz sentido para o negócio

📌 Quando usar:
- Requisitos legais
- Baixo valor em migrar

---

### ❌ Retire (Retirar / Destivar)
- Desligar aplicação

📌 Quando usar:
- Sistema obsoleto
- Sem uso

---

## 🧠 Conceitos importantes

### ⚡ Trade-off
- Quanto mais mudança → maior esforço
- Quanto menos mudança → migração mais rápida

---

### 🧩 Estratégias podem coexistir
- Uma empresa pode usar várias estratégias ao mesmo tempo

---

## ⚖️ Comparações importantes

### Rehost vs Refactor

| Rehost | Refactor |
|--------|----------|
| Rápido | Complexo |
| Sem mudanças | Reescrito |
| Baixo custo inicial | Alto investimento |
| Pouco ganho | Alto ganho |

---

### Replatform vs Repurchase

| Replatform | Repurchase |
|------------|------------|
| Ajuste leve | Troca total |
| Mantém sistema | Novo sistema |
| Menor impacto | Maior mudança |

---

## 🚀 Benefícios

- Flexibilidade na migração
- Redução de riscos
- Planejamento estruturado
- Otimização de custos e performance

---

## 🧠 Conceitos importantes para prova

- Existem **6 estratégias (6 Rs)**
- Rehost = lift-and-shift
- Refactor = cloud-native
- Retire = desativar
- Repurchase = SaaS

---

## ⚠️ Pegadinhas comuns

- Confundir Rehost com Replatform
- Achar que todas aplicações precisam ser refatoradas
- Ignorar estratégia Retain
- Esquecer que Retire também é estratégia

---

## 🔁 Resumo rápido

- 6 Rs = estratégias de migração
- Variam de simples → complexas
- Podem ser combinadas
- Dependem do contexto da aplicação

---

## 📌 Status de aprendizado

- [ ] Sei as 6 estratégias (6 Rs)
- [ ] Entendo quando usar cada uma
- [ ] Sei diferenças entre elas
- [ ] Consigo identificar exemplos

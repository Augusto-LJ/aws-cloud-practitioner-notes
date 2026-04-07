# 🏗️ Infrastructure as Code (IaC) na AWS

## 📌 O que é

Infrastructure as Code (IaC) é a prática de **provisionar infraestrutura usando código**, em vez de criar recursos manualmente pelo console.

---

## 🎯 Objetivo

- Automatizar criação de infraestrutura
- Garantir consistência
- Evitar erros manuais
- Facilitar reprodução de ambientes

---

## ⚙️ Como funciona

Em vez de:

- Criar recursos manualmente no console

Você:

- Escreve um arquivo de configuração
- Executa esse código
- AWS cria todos os recursos automaticamente

---

## 📦 Exemplo de uso

Você pode definir:

- EC2
- Banco de dados
- Redes
- Load balancers

Tudo em um único arquivo

---

## 🔁 Benefícios

### ♻️ Reprodutibilidade
- Criar o mesmo ambiente várias vezes

---

### 🧪 Consistência
- Evita erros humanos

---

### ⚡ Automação
- Sem necessidade de ações manuais

---

### 📜 Versionamento
- Código pode ser versionado (Git)

---

## 🧱 AWS CloudFormation

### 📌 O que é

O AWS CloudFormation é o serviço da AWS para implementar Infrastructure as Code.

---

### ⚙️ Como funciona

- Você define um template (JSON ou YAML)
- O CloudFormation cria os recursos automaticamente
- Os recursos são organizados em uma "stack"

---

### 📦 Stack

- Conjunto de recursos criados juntos
- Gerenciados como uma unidade

---

## 🔄 Provisionamento seguro

O CloudFormation:

- Cria recursos na ordem correta
- Gerencia dependências automaticamente

---

## 🛡️ Rollback automático

Se ocorrer erro durante criação:

- CloudFormation desfaz tudo automaticamente
- Evita ambientes inconsistentes

---

## 🚀 Casos de uso

- Criar ambientes de desenvolvimento/teste
- Deploy de infraestrutura em produção
- Automação de arquitetura
- Padronização de ambientes

---

## ⚖️ Comparações importantes

### IaC vs criação manual

| IaC | Manual |
|-----|--------|
| Automatizado | Manual |
| Reproduzível | Difícil de repetir |
| Versionável | Não |
| Menos erro | Mais erro |

---

### CloudFormation vs Console

| CloudFormation | Console |
|---------------|--------|
| Código | Interface gráfica |
| Automação | Manual |
| Escalável | Limitado |

---

## 🧠 Conceitos importantes para prova

- IaC = infraestrutura via código
- CloudFormation é o serviço da AWS para IaC
- Usa templates JSON/YAML
- Stack = conjunto de recursos
- Suporte a rollback automático

---

## ⚠️ Pegadinhas comuns

- Achar que IaC é apenas script (é conceito)
- Confundir CloudFormation com CLI
- Ignar rollback automático
- Pensar que substitui todos os serviços (ele apenas orquestra)

---

## 🔁 Resumo rápido

- IaC = automatizar infraestrutura com código
- CloudFormation = ferramenta AWS para IaC
- Seguro, reproduzível e escalável

---

## 📌 Status de aprendizado

- [ ] Entendo o que é IaC
- [ ] Sei o que é CloudFormation
- [ ] Entendo o conceito de stack
- [ ] Sei vantagens sobre criação manual

# 🏢 AWS Organizations

## 📌 O que é

O AWS Organizations é um serviço que permite **gerenciar múltiplas contas AWS de forma centralizada**.

Ele facilita o controle de permissões, custos e políticas em um ambiente com várias contas.

---

## 🎯 Quando usar

- Empresas com múltiplas contas AWS
- Separação de ambientes (dev, test, prod)
- Controle centralizado de permissões
- Governança e compliance

---

## ⚙️ Como funciona

- Você cria uma organização
- Adiciona contas à organização
- Agrupa contas em unidades organizacionais (OUs)
- Aplica políticas centralizadas

---

## 📦 Conceitos importantes

### 🧾 Conta raiz (Management Account)
- Conta principal da organização
- Responsável por gerenciar as demais

---

### 🏢 Contas membro
- Contas que fazem parte da organização

---

### 🧩 Unidade Organizacional (Organizational Unit ou OU)
- Grupo de contas
- Permite organizar por:
  - Ambiente (dev, prod)
  - Departamento
  - Projeto

---

### 📜 SCP (Service Control Policy)
- Políticas que definem o que as contas podem ou não fazer
- Aplicadas em nível de organização
- Podem ser aplicadas à raiz da organização, a uma conta de membro individual ou a uma unidade organizacional (OU)

---

## 🔐 Controle centralizado

- Definir permissões globais
- Restringir serviços
- Padronizar segurança

---

## 💰 Gestão de custos

- Faturamento consolidado
- Visualização centralizada de gastos
- Possibilidade de descontos por volume

---

## 🚀 Casos de uso

- Empresas com múltiplos times
- Separação de ambientes
- Governança corporativa
- Controle de custos

---

## ⚖️ Comparações importantes

### Organizations vs IAM

| Organizations | IAM |
|--------------|-----|
| Multi-conta | Conta única |
| Controle global | Controle local |
| Usa SCP | Usa policies |

---

## 🧠 Conceitos importantes para prova

- Organizations = múltiplas contas
- SCP limita permissões
- OU organiza contas
- Faturamento consolidado

---

## ⚠️ Pegadinhas comuns

- SCP não concede permissões, apenas restringe
- Não substitui IAM
- Conta raiz tem controle total
- Não é apenas para custos (também governança)

---

## 🔁 Resumo rápido

- Organizations = gestão de múltiplas contas
- Controle centralizado
- Uso de SCP para restrições
- Ideal para empresas

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Organizations
- [ ] Sei o que é OU
- [ ] Entendo SCP
- [ ] Sei diferença entre IAM e Organizations

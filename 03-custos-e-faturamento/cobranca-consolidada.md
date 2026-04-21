# 🧾 Cobrança Consolidada na AWS (Faturamento Consolidado)

## 📌 O que é

A Cobrança Consolidada é um recurso do AWS Organizations que permite **centralizar o faturamento de várias contas AWS em uma única conta principal (conta pagadora)**.

Isso facilita o gerenciamento financeiro e permite otimizar custos.

---

## 🎯 Quando usar

- Empresas com múltiplas contas AWS
- Separação de ambientes (dev, teste, produção)
- Organizações com várias equipes ou projetos
- Centralizar cobrança e pagamento

---

## ⚙️ Como funciona

- Uma conta é definida como **conta pagadora (management account)**
- Outras contas são vinculadas a ela
- Todos os custos são consolidados em uma única fatura

---

## 📦 Conceitos importantes

### 🧾 Conta pagadora (Management Account)
- Responsável pelo pagamento de todas as contas
- Visualiza custos consolidados

---

### 👥 Contas vinculadas (Member Accounts)
- Contas individuais da organização
- Geram custos, mas não pagam diretamente

---

### 📊 Fatura única
- Todos os custos aparecem em um único relatório
- Pode ser detalhado por conta

---

## 💰 Benefícios

### 📉 Descontos por volume
- Uso agregado pode gerar descontos maiores
- Exemplo:
  - Uma conta pode não ter uso mensal suficiente para se qualificar para preços com desconto
  - No entanto, quando várias contas são combinadas, o uso agregado pode resultar em um benefício que se aplica a todas as contas na organização

---

### 📊 Visibilidade centralizada
- Visualiza gastos de todas as contas em um único lugar

---

### 🧩 Organização financeira
- Separação por projetos ou equipes
- Controle mais eficiente

---

## 🔗 Integração

- AWS Organizations
- AWS Cost Explorer (visualização por conta)
- AWS Budgets (alertas por conta ou organização)

---

## ⚖️ Comparações importantes

### Conta única vs Cobrança consolidada

| Conta única | Cobrança consolidada |
|------------|---------------------|
| Uma conta só | Várias contas |
| Gestão simples | Gestão centralizada |
| Sem separação | Separação por equipes/projetos |

---

### Cobrança consolidada vs contas independentes

| Consolidada | Independentes |
|------------|---------------|
| Uma fatura | Várias faturas |
| Descontos por volume | Sem agregação |
| Controle central | Controle isolado |

---

## 🧠 Conceitos importantes para prova

- Cobrança consolidada = múltiplas contas, uma fatura
- Faz parte do AWS Organizations
- Permite descontos por volume
- Conta pagadora centraliza custos

---

## ⚠️ Pegadinhas comuns

- Confundir com compartilhamento de recursos (não é isso)
- Achar que as contas perdem autonomia (não perdem)
- Pensar que elimina necessidade de controle individual
- Achar que todas as contas veem tudo (depende de permissões)

---

## 🔁 Resumo rápido

- Centraliza faturamento de várias contas
- Usa AWS Organizations
- Permite economia por volume
- Facilita gestão financeira

---

## 📌 Status de aprendizado

- [ ] Entendo o que é cobrança consolidada
- [ ] Sei o que é conta pagadora
- [ ] Entendo benefícios de custo
- [ ] Sei quando usar

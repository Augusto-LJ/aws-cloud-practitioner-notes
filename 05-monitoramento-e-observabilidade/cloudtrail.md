# 📜 AWS CloudTrail

## 📌 O que é

O AWS CloudTrail é um serviço que permite **auditar e registrar todas as ações realizadas na sua conta AWS**.

Ele registra quem fez o quê, quando fez e a partir de onde, fornecendo **rastreabilidade completa** das atividades.

---

## 🎯 Quando usar

- Auditoria de segurança
- Investigação de incidentes
- Compliance e conformidade
- Monitoramento de atividades da conta

---

## ⚙️ Como funciona

- Registra chamadas de API realizadas na AWS
- Armazena logs de eventos
- Permite análise e rastreamento de ações

---

## 📦 Conceitos importantes

### 📄 Eventos (Events)
- Registros de ações realizadas na AWS
- Exemplo:
  - Criar uma instância EC2
  - Deletar um bucket S3

---

### 👤 Identidade
- Mostra quem realizou a ação:
  - Usuário IAM
  - Role
  - Serviço AWS

---

### 📜 CloudTrail Insights
- Recurso opcional que permite que o CloudTrail detecte automaticamente atividades de API incomuns em sua conta AWS
  - Por exemplo, o CloudTrail Insights pode detectar que mais instâncias do Amazon EC2 do que o normal foram iniciadas recentemente em sua conta.
  - Em seguida, você pode revisar os detalhes completos do evento para determinar quais ações precisa executar a seguir.

--- 

### 🌍 Origem da requisição
- Indica de onde a ação foi realizada (IP, região, etc)

---

### 🕒 Histórico de eventos
- Permite visualizar ações recentes diretamente no console

---

## 📊 Tipos de eventos

### 🔹 Management Events
- Ações de gerenciamento
- Ex:
  - Criar recursos
  - Alterar configurações

---

### 🔹 Data Events
- Ações em dados
- Ex:
  - Leitura/escrita em S3
  - Operações no DynamoDB

---

## 🔗 Integração

- Amazon S3 (armazenamento de logs)
- Amazon CloudWatch (monitoramento e alertas)
- AWS Lambda (automação)

---

## 🔒 Segurança

- Ajuda na detecção de atividades suspeitas
- Fornece trilha de auditoria completa
- Fundamental para compliance

---

## ⚖️ Comparações importantes

### CloudTrail vs CloudWatch

| CloudTrail | CloudWatch |
|------------|-----------|
| Auditoria de ações | Monitoramento de métricas |
| Quem fez o quê | Performance e logs |
| Segurança e compliance | Observabilidade |

---

### CloudTrail vs GuardDuty

| CloudTrail | GuardDuty |
|------------|-----------|
| Registra eventos | Detecta ameaças |
| Dados brutos | Análise inteligente |
| Auditoria | Segurança ativa |

---

## 🧠 Conceitos importantes para prova

- CloudTrail = auditoria de ações
- Registra chamadas de API
- Mostra quem fez o quê
- Usado para segurança e compliance

---

## ⚠️ Pegadinhas comuns

- Não monitora performance (isso é CloudWatch)
- Não bloqueia ações
- Não analisa automaticamente (isso é GuardDuty)

---

## 🔁 Resumo rápido

- CloudTrail = auditoria da AWS
- Registra ações da conta
- Ajuda em segurança e compliance
- Integra com outros serviços

---

## 📌 Status de aprendizado

- [ ] Entendo o que é CloudTrail
- [ ] Sei o que são eventos
- [ ] Entendo diferença para CloudWatch
- [ ] Sei quando usar

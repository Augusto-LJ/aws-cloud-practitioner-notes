# 🔒 Modelo de Responsabilidade Compartilhada

## 📌 O que é

O modelo de responsabilidade compartilhada define **quais responsabilidades são da AWS e quais são do cliente** na computação em nuvem.

👉 Nem tudo é responsabilidade da AWS — o cliente também precisa cuidar de parte da segurança e configuração.

---

## ⚖️ Como funciona

A responsabilidade é dividida em duas partes:
<img width="979" height="535" alt="image" src="https://github.com/user-attachments/assets/88ded5c7-a189-4c51-9525-9c23bdd625eb" />

- **AWS → segurança "da" nuvem (of the Cloud)**
- **Cliente → segurança "na" nuvem (in the Cloud)**

---

## 🏢 Responsabilidades da AWS (of the Cloud)

A AWS é responsável pela **infraestrutura física e serviços subjacentes**:
<img width="931" height="359" alt="image" src="https://github.com/user-attachments/assets/1b09d95b-2962-4add-a1f7-871de90f5cdd" />

👉 Ou seja: tudo que está **abaixo da camada do sistema operacional**

---

## 👤 Responsabilidades do Cliente (in the Cloud)

O cliente é responsável por tudo que configura e utiliza:
<img width="928" height="394" alt="image" src="https://github.com/user-attachments/assets/335ee9df-4cd8-4d34-956b-4b3b846cf85a" />

👉 Ou seja: tudo que você **instala, configura ou armazena**

---

## 🔄 Variação por tipo de serviço

A responsabilidade do cliente muda dependendo do modelo:

---

### 🖥️ IaaS (ex: EC2)

Você gerencia:
- Sistema operacional
- Aplicações
- Segurança do sistema

AWS gerencia:
- Infraestrutura

👉 Maior controle = maior responsabilidade

---

### ⚙️ PaaS (ex: RDS, Elastic Beanstalk)

Você gerencia:
- Dados
- Aplicações

AWS gerencia:
- Sistema operacional
- Infraestrutura

---

### ⚡ Serverless (ex: Lambda)

Você gerencia:
- Código
- Permissões
- Dados

AWS gerencia:
- Infraestrutura
- Sistema operacional
- Escalabilidade

👉 Menos responsabilidade para o cliente

---

## 🔐 Exemplos práticos

### EC2
- AWS cuida do servidor físico
- Você cuida de:
  - Atualizações do sistema
  - Segurança
  - Configuração

---

### S3
- AWS cuida da infraestrutura
- Você cuida de:
  - Permissões (quem pode acessar)
  - Configuração de acesso público

---

## 🧠 Conceitos importantes para prova

- AWS não cuida de tudo
- Cliente sempre é responsável pelos dados
- Responsabilidade varia conforme o serviço
- Quanto mais gerenciado o serviço, menor sua responsabilidade

---

## ⚠️ Pegadinhas comuns

- Achar que AWS protege seus dados automaticamente
- Esquecer de configurar permissões no S3
- Pensar que serverless não exige segurança
- Confundir responsabilidade da AWS com do cliente

---

## 🔁 Resumo rápido

- Segurança é compartilhada
- AWS cuida da infraestrutura
- Cliente cuida dos dados e configurações
- Responsabilidade depende do tipo de serviço

---

## 📌 Status de aprendizado

- [ ] Entendo o modelo de responsabilidade compartilhada
- [ ] Sei o que é responsabilidade da AWS
- [ ] Sei o que é responsabilidade do cliente
- [ ] Entendo como isso muda entre EC2, RDS e Lambda

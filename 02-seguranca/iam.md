# 🔐 IAM (Identity and Access Management)

## 📌 O que é

O IAM (Identity and Access Management) é o serviço da AWS responsável por **controle de acesso e permissões**.

Ele define **quem pode acessar o quê** dentro da sua conta AWS.

---

## 🎯 Quando usar

- Controlar acesso de usuários e sistemas
- Definir permissões para serviços (ex: EC2 acessar S3)
- Gerenciar autenticação e autorização

---

## ⚙️ Como funciona

- Você cria identidades (usuários, grupos, roles)
- Define permissões através de políticas (policies)
- Associa essas políticas às identidades

---

## 📦 Conceitos importantes

### 👤 Usuário (User)
- Representa uma pessoa ou aplicação
- Possui credenciais de acesso

---

### 👥 Grupo (Group)
- Conjunto de usuários com mesmas permissões
- Facilita gerenciamento de permissões

---

### 🎭 Role (Função)
- Permissão temporária assumida por:
  - Serviços AWS
  - Aplicações
  - Usuários

👉 Muito usada para integração entre serviços

---

### 📜 Policy (Política)
- Documento JSON que define permissões
- Especifica:
  - Ações permitidas ou negadas
  - Recursos
  - Condições

---

## 🔑 Tipos de acesso

### Console
- Login com usuário e senha

---

### Programático
- Access Key + Secret Key
- Usado por aplicações e APIs

---

## 🔒 Boas práticas

- Usar **roles** ao invés de credenciais fixas
- Aplicar o princípio do **menor privilégio**: dar a menor quantidade possível de permissões a um usuário
- Evitar uso da conta root
- Habilitar MFA (autenticação multifator)

---

## ⚖️ Comparações importantes

### User vs Role

| User | Role |
|------|------|
| Acesso permanente | Acesso temporário |
| Credenciais próprias | Sem credenciais fixas |
| Usado por pessoas | Usado por serviços/aplicações |

---

### Policy vs Role

| Policy | Role |
|--------|------|
| Define permissões | Assume permissões |
| Documento JSON | Identidade |

---

## 🧠 Conceitos importantes para prova

- IAM controla acesso à AWS
- Policies definem permissões
- Roles são usadas para acesso temporário
- Princípio do menor privilégio é essencial
- MFA aumenta segurança

---

## ⚠️ Pegadinhas comuns

- Usar conta root no dia a dia
- Dar permissões excessivas
- Confundir role com usuário
- Armazenar access keys de forma insegura

---

## 🔁 Resumo rápido

- IAM = controle de acesso
- Define quem pode fazer o quê
- Usa users, groups, roles e policies
- Segurança baseada em permissões

---

## 📌 Status de aprendizado

- [ ] Entendo o que é IAM
- [ ] Sei diferença entre user, group e role
- [ ] Entendo policies
- [ ] Conheço boas práticas de segurança

# 🔐 IAM (Identity and Access Management)

## 📌 O que é

O IAM (Identity and Access Management) é o serviço da AWS responsável por **controle de acesso e permissões**.

Ele define **quem pode acessar o quê** dentro da sua conta AWS e oferece a flexibilidade de configurar o acesso com base nas necessidades operacionais e de segurança específicas do sistema ou da empresa

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

### 🌱 Usuário raiz (Root user)
- É o usuário criado ao criar uma conta AWS
- Tem acesso completo a todos os serviços e recursos AWS na conta
- Não é recomendado utilizar o usuário raiz para tarefas cotidianas
  - Em vez disso, use o usuário-raiz para criar seu primeiro usuário do IAM e atribua a ele permissões para criar outros usuários.

---

### 👤 Usuário do IAM (IAM User)
- Representa uma pessoa ou aplicação
  - Recomendado que cada pessoa que precisa acessar a AWS tenha seu próprio usuário
- Possui um nome e credenciais de acesso
- Por padrão, ao ser criado, não possui nenhuma permissão

---

### 📜 Política do IAM (IAM Policy)
- Documento JSON que concede ou nega permissões
- Possibilita personalizar os níveis de acesso dos usuários aos recursos
- Exemplo de política IAM:
<img width="524" height="407" alt="image" src="https://github.com/user-attachments/assets/e1532b95-9d1c-4cf3-a561-0b15113a6fe0" />

---

### 👥 Grupo do IAM (IAM Group)
- Conjunto de usuários com mesmas permissões
  - Quando atribui uma política do IAM a um grupo, todos os usuários do grupo recebem permissões especificadas pela política
- Facilita gerenciamento de permissões

---

### 🎭 Perfis do IAM (IAM Roles)
- Permissão temporária assumida por:
  - Serviços AWS
  - Aplicações
  - Usuários
- Assumir um perfil significa revogar as permissões do perfil anterior e obter as permissões do novo perfil
- São ideais para situações em que o acesso a serviços ou recursos precisa ser concedido temporariamente, em vez de por longo prazo

👉 Muito usada para integração entre serviços

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
  - Por exemplo, se um funcionário precisar acessar apenas um bucket específico, especifique o bucket na política do IAM vez de conceder ao funcionário acesso a todos os buckets
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

# 🔐 AWS Key Management Service (KMS)

## 📌 O que é

O AWS KMS é um serviço que permite **criar e gerenciar chaves de criptografia** para proteger dados na AWS.

Ele é usado para realizar operações de **criptografia e descriptografia** de forma segura.

---

## 🎯 Quando usar

- Proteger dados sensíveis
- Implementar criptografia em aplicações
- Atender requisitos de segurança e conformidade
- Controlar acesso a dados criptografados

---

## ⚙️ Como funciona

- Você cria chaves de criptografia (KMS Keys)
- Usa essas chaves para criptografar dados
- Controla quem pode usar as chaves via IAM

---

## 📦 Conceitos importantes

### 🔑 Chave de criptografia
- Sequência usada para criptografar e descriptografar dados

---

### 🔒 Criptografia em repouso
- Dados armazenados protegidos

---

### 🔄 Criptografia em trânsito
- Dados protegidos durante envio

---

### 👤 Controle de acesso
- Definido via IAM
- Permite restringir quem pode usar as chaves

---

## 🔐 Segurança

- Chaves nunca saem do KMS
- Controle total sobre uso das chaves
- Possibilidade de desativar chaves

---

## 🔗 Integração

- Amazon S3
- Amazon EBS
- Amazon RDS
- Outros serviços AWS

---

## ⚖️ Comparações importantes

### KMS vs Criptografia manual

| KMS | Manual |
|-----|--------|
| Gerenciado pela AWS | Gerenciado pelo usuário |
| Seguro | Mais risco |
| Integrado com AWS | Mais complexo |

---

## 🧠 Conceitos importantes para prova

- KMS = criptografia
- Gerencia chaves
- Integra com vários serviços
- Usa IAM para controle

---

## ⚠️ Pegadinhas comuns

- KMS não armazena dados (apenas chaves)
- Não substitui controle de acesso (IAM)
- Criptografia não é automática (precisa configurar)

---

## 🔁 Resumo rápido

- KMS = gerenciamento de chaves
- Protege dados com criptografia
- Integrado com AWS
- Controle via IAM

---

## 📌 Status de aprendizado

- [ ] Entendo o que é KMS
- [ ] Sei diferença entre criptografia em repouso e em trânsito
- [ ] Entendo controle de acesso via IAM
- [ ] Sei quando usar KMS

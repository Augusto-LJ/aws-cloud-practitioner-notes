# 🌐 VPC (Virtual Private Cloud)

## 📌 O que é

A VPC (Virtual Private Cloud) é um serviço da AWS que permite criar uma **rede virtual isolada** dentro da nuvem.

É onde você define como seus recursos (EC2, RDS, etc.) se comunicam entre si e com a internet.

---

## 🎯 Quando usar

- Sempre que criar recursos na AWS (quase tudo roda dentro de uma VPC)
- Quando precisar controlar rede, IPs e segurança
- Para isolar ambientes (ex: dev, homologação, produção)

---

## ⚙️ Como funciona

- Você cria uma VPC com um bloco de IP (CIDR)
- Divide em sub-redes (subnets)
- Configura regras de acesso e roteamento

---

## 📦 Conceitos importantes

### 🧱 CIDR Block
- Faixa de IPs da VPC
- Exemplo: 10.0.0.0/16

---

### 🏠 Subnet (Sub-rede)
- Divisão da VPC
- Pode ser:
  - Pública (com acesso à internet)
  - Privada (sem acesso direto)

---

### 🌍 Internet Gateway (IGW)
<img width="909" height="501" alt="image" src="https://github.com/user-attachments/assets/a47cdbb3-f383-4eb4-b3b0-7d42e01a0b8d" />

- Permite comunicação entre a VPC e a internet

---

### 🌍 Gateway privado virtual
<img width="934" height="438" alt="image" src="https://github.com/user-attachments/assets/29aab26e-7f27-4628-88ac-89fd3d24119f" />

- Permite acessar recursos privados em uma VPC, estabelecendo uma conexão VPN entre a VPC e uma rede privada

### 🔄 Route Table
- Define para onde o tráfego deve ir
- Exemplo:
  - 0.0.0.0/0 → Internet Gateway

---

### 🔐 Security Groups
- Firewall das instâncias (stateful)

---

### 🚧 NACL (Network ACL)
- Firewall da sub-rede (stateless)

---

## 🌐 Subnet pública vs privada

### Subnet pública
- Tem rota para Internet Gateway
- Recursos podem ter IP público

---

### Subnet privada
- Sem acesso direto à internet
- Usada para bancos de dados, serviços internos

---

## 🔒 Segurança na VPC

- Security Groups → nível de instância
- NACL → nível de sub-rede
- Controle total do tráfego

---

## 📈 Alta disponibilidade

- Use múltiplas subnets em diferentes AZs
- Distribua recursos entre elas

---

## ⚖️ Comparações importantes

### Security Group vs NACL

| Security Group | NACL |
|----------------|------|
| Stateful | Stateless |
| Nível da instância | Nível da sub-rede |
| Mais simples | Mais granular |

---

## 🧠 Conceitos importantes para prova

- VPC = rede virtual isolada
- Subnets podem ser públicas ou privadas
- Internet Gateway permite acesso à internet
- Security Group é stateful
- NACL é stateless

---

## ⚠️ Pegadinhas comuns

- Subnet não é automaticamente pública (precisa de rota)
- Security Group ≠ NACL
- Recursos privados ainda podem acessar internet (via NAT, por exemplo)
- Tudo na AWS roda dentro de uma VPC

---

## 🔁 Resumo rápido

- VPC = sua rede dentro da AWS
- Controle total de IP, sub-redes e segurança
- Base para todos os serviços

---

## 📌 Status de aprendizado

- [ ] Entendo o que é VPC
- [ ] Sei diferença entre subnet pública e privada
- [ ] Entendo Security Group vs NACL
- [ ] Sei o papel do Internet Gateway

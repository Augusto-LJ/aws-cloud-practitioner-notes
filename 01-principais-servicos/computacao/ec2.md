# 🖥️ EC2 (Elastic Compute Cloud)

## 📌 O que é

O EC2 (Elastic Compute Cloud) é um serviço de computação da AWS que fornece **máquinas virtuais sob demanda**.

Permite que você execute aplicações em servidores virtuais, com controle total sobre o sistema operacional e configurações.

---

## 🎯 Quando usar

- Quando precisa de controle total do ambiente (SO, runtime, rede)
- Aplicações tradicionais (ex: APIs em .NET, Java, Node.js)
- Sistemas legados
- Workloads que não são facilmente serverless

---

## ⚙️ Conceitos importantes

### 🧱 Instância
- Máquina virtual em execução na AWS

---

### 💿 AMI (Amazon Machine Image)
- Template usado para criar instâncias
- Contém:
  - Sistema operacional
  - Configurações iniciais
  - Softwares pré-instalados

---

### 📦 Tipos de instância (Instance Types)

São eles:
- **Uso geral** → É balanceado e usado para diversos workloads diferentes
- **Otimizada para computação (CPU)** → Processadores de alta performance. Ideal para computação excessiva e workloads de processamento em lote
- **Otimizado para memória (RAM)** → Memórias de alta performance. Ideal para bancos de dados de alta performance
- **Computação acelerada (GPU)** → Aceleradores de hardware para agilizar processamento de dados. Ideal para streaming de aplicações e workloads gráficos
- **Otimizada para armazenamento** → Baixa latência a alta taxa de entrada/saída por segundo (IOPS). Ideal para workloads de sistemas distribuídos e aplicações de data warehousing 

👉 Cada tipo define:
- CPU
- Memória
- Rede

---

### 🔐 Security Groups
- Firewall da instância
- Controla tráfego:
  - Entrada (inbound)
  - Saída (outbound)

📌 Características:
- Stateful (resposta liberada automaticamente)
- Baseado em regras (porta, IP, protocolo)

---

### 🌐 Key Pair
- Usado para acesso SSH (Linux) ou descriptografia (Windows)
- Composto por:
  - Chave pública (AWS)
  - Chave privada (você)

---

### 📈 Auto Scaling
- Ajusta automaticamente a quantidade de instâncias
- Baseado em métricas (CPU, tráfego, etc.)

---

### ⚖️ Load Balancer (ELB)
- Distribui tráfego entre múltiplas instâncias
- Aumenta disponibilidade

---

## 💾 Armazenamento no EC2

### EBS (Elastic Block Store)
- Disco anexado à instância
- Persistente
- Pode ser destacado e reutilizado

---

### Instance Store
- Armazenamento temporário
- Dados são perdidos ao parar/parar instância

---

## 💰 Modelos de cobrança

### On-Demand
- Paga por uso (por hora/segundo)
- Sem compromisso

---

### Reserved Instances
- Contrato de 1 ou 3 anos
- Mais barato que On-Demand

---

### Spot Instances
- Usa capacidade ociosa da AWS
- Muito mais barato
- Pode ser interrompido a qualquer momento

---

### Savings Plans
- Compromisso de uso (em $/hora)
- Flexível e com desconto

---

## 🔒 Responsabilidade no EC2

### AWS cuida de:
- Hardware
- Infraestrutura física
- Data centers

### Você cuida de:
- Sistema operacional
- Atualizações (patches)
- Segurança da aplicação
- Configuração de rede (Security Groups)

---

## 📈 Alta disponibilidade no EC2

Para alta disponibilidade, use:
- Múltiplas AZs
- Load Balancer
- Auto Scaling

---

## 🔁 Comparações importantes

### EC2 vs Lambda

| EC2 | Lambda |
|-----|--------|
| Controle total | Sem gerenciamento de servidor |
| Precisa gerenciar SO | AWS gerencia tudo |
| Ideal para apps longos | Ideal para execuções curtas |

---

### EC2 vs Elastic Beanstalk

| EC2 | Elastic Beanstalk |
|-----|------------------|
| Baixo nível | Alto nível (PaaS) |
| Controle total | Automatiza deploy |

---

## 🧠 Conceitos importantes para prova

- EC2 = IaaS
- Você tem controle total do sistema operacional
- Security Group é **stateful**
- Pode escalar automaticamente (Auto Scaling)
- Pode usar diferentes modelos de preço

---

## ⚠️ Pegadinhas comuns

- Security Group ≠ NACL (NACL é stateless)
- EC2 não é serverless
- Parar instância não significa custo zero (EBS continua cobrando)
- Spot Instances podem ser interrompidas

---

## 🔁 Resumo rápido

- EC2 = máquina virtual na AWS
- Total controle sobre o ambiente
- Escalável com Auto Scaling
- Protegido por Security Groups
- Cobrança flexível (On-Demand, Reserved, Spot)

---

## 📌 Status de aprendizado

- [ ] Sei o que é uma instância EC2
- [ ] Entendo AMI e tipos de instância
- [ ] Sei como funciona Security Group
- [ ] Entendo os modelos de cobrança
- [ ] Sei quando usar EC2 vs Lambda

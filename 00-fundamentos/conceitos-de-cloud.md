# ☁️ Conceitos de Cloud

## 📌 O que é Cloud Computing

Cloud Computing (Computação em Nuvem) é a entrega de recursos de TI sob demanda pela internet, com modelo de pagamento conforme o uso (*pay-as-you-go*).

Em vez de comprar e manter servidores físicos, você utiliza infraestrutura, armazenamento, bancos de dados e outros serviços fornecidos por provedores como a AWS.

---

## 🎯 Vantagens da Computação em Nuvem

### 1. Trocar CapEx por OpEx
- **CapEx (Capital Expenditure)**: investimento inicial alto (servidores físicos)
- **OpEx (Operational Expenditure)**: pagamento conforme uso

👉 Você paga apenas pelo que consumir

---

### 2. Escalabilidade sob demanda
- Aumente ou reduza recursos rapidamente
- Exemplo: lidar com picos de acesso sem precisar prever capacidade

---

### 3. Alta disponibilidade
- Infraestrutura distribuída globalmente
- Menor risco de downtime

---

### 4. Velocidade e agilidade
- Provisionamento em minutos
- Não precisa comprar hardware

---

### 5. Economia de escala
- AWS tem custo menor por operar em grande escala
- Repasse de economia para o cliente

---

## 🏗️ Modelos de Serviço (Service Models)

### IaaS (Infrastructure as a Service)
- Controle total sobre infraestrutura
- Você gerencia:
  - Sistema operacional
  - Aplicações
- Exemplo: EC2

---

### PaaS (Platform as a Service)
- AWS gerencia infraestrutura + sistema operacional
- Você foca na aplicação
- Exemplo: Elastic Beanstalk

---

### SaaS (Software as a Service)
- Aplicação pronta para uso
- Usuário final apenas consome
- Exemplo: Gmail, Dropbox

---

## 🏢 Modelos de Implantação (Deployment Models)

### 1. Cloud Pública
- Infraestrutura compartilhada
- Mantida pelo provedor (AWS)

---

### 2. Cloud Privada
- Infraestrutura exclusiva de uma empresa
- Pode ser on-premise ou hospedada

---

### 3. Cloud Híbrida
- Combinação de cloud + infraestrutura local

---

## ⚙️ Principais Conceitos da AWS

### 🌍 Regiões (Regions)
- Localizações físicas ao redor do mundo
- Exemplo: sa-east-1 (São Paulo)

---

### 🏢 Zonas de Disponibilidade (AZ - Availability Zones)
- Data centers isolados dentro de uma região
- Alta disponibilidade e tolerância a falhas

---

### 🌐 Pontos de presença (Edge Locations)
- Usadas para CDN (CloudFront)
- Aproximam conteúdo do usuário final, diminuindo a latência

---

## 🔒 Modelo de Responsabilidade Compartilhada (resumo)

- **AWS (of the Cloud)**:
  - Infraestrutura física
  - Data centers
  - Hardware

- **Cliente (in the Cloud)**:
  - Configurações
  - Dados
  - Controle de acesso

---

## 📈 Escalabilidade vs Elasticidade

### Escalabilidade
- Aumentar capacidade para suportar crescimento

### Elasticidade
- Ajustar automaticamente conforme demanda

👉 Elasticidade = escalabilidade automática

---

## 💰 Alta Disponibilidade vs Tolerância a Falhas

### Alta Disponibilidade
- Sistema continua operando mesmo com falhas
- Pode haver pequena interrupção

### Tolerância a Falhas
- Nenhuma interrupção percebida
- Sistema totalmente redundante

---

## 🧠 Conceitos importantes para prova

- Cloud = sob demanda + pagamento por uso
- Evitar investimento inicial alto (CapEx)
- Elasticidade é um diferencial chave
- Regiões ≠ Zonas de disponibilidade
- Modelo de responsabilidade é frequentemente cobrado
- Alta disponibilidade ≠ tolerância a falhas

---

## ⚠️ Pegadinhas comuns

- Confundir **Região** com **AZ**
- Achar que AWS cuida de tudo (não cuida)
- Confundir escalabilidade com elasticidade
- Achar que SaaS dá controle de infraestrutura (não dá)

---

## 🔁 Resumo rápido

- Cloud = recursos sob demanda via internet
- Pague apenas pelo uso
- Escalável, elástico e altamente disponível
- AWS divide responsabilidade com você
- Infraestrutura global distribuída

---

## 📌 Status de aprendizado

- [ ] Entendo os modelos (IaaS, PaaS, SaaS)
- [ ] Sei diferença entre Região e AZ
- [ ] Entendo responsabilidade compartilhada
- [ ] Sei explicar elasticidade vs escalabilidade

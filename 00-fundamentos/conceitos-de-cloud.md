# ☁️ Conceitos de Cloud

## 📌 O que é Cloud Computing

Cloud Computing (Computação em Nuvem) é a entrega de recursos de TI sob demanda pela internet, com modelo de pagamento conforme o uso (*pay-as-you-go*).

Em vez de comprar e manter servidores físicos, você utiliza infraestrutura, armazenamento, bancos de dados e outros serviços fornecidos por provedores como a AWS.

---

## 🎯 Benefícios da Computação em Nuvem

### 1. Troque despesas iniciais por despesas variáveis
- Despesas iniciais são data centers, servidores físicos e outros recursos nos quais você precisaria investir antes de usá-los
- Em vez de investir substancialmente em data centers e servidores antes de saber como serão usados, você pode pagar somente ao consumir recursos de computação.

---

### 2. Beneficie-se de grandes economias de escala
- O uso da computação em nuvem permite obter um custo variável menor ao que você conseguiria por conta própria
- As economias de escala se transformam em preços para pagamento conforme o uso mais baixos.
---

### 3. Pare de tentar adivinhar a capacidade
- Com a computação em nuvem, você não precisa prever a capacidade de infraestrutura necessária antes de implantar uma aplicação
- Por exemplo, você pode iniciar instâncias do Amazon EC2 quando necessário e pagar apenas pelo tempo de computação usado.
- Em vez de pagar por recursos que não são utilizados ou lidar com capacidade limitada, você pode acessar somente a capacidade de que precisa e aumentar ou reduzir a quantidade em resposta à demanda. 

---

### 4. Aumente a velocidade e a agilidade
- A flexibilidade da computação em nuvem facilita o desenvolvimento e a implantação de aplicações
- Essa flexibilidade também oferece às suas equipes de desenvolvimento mais tempo para experimentar e inovar

---

### 5. Pare de gastar dinheiro com execução e manutenção de data centers
- A computação em nuvem em data centers geralmente exige que você gaste mais dinheiro e tempo gerenciando infraestrutura e servidores
- Um benefício da computação em nuvem é poder se concentrar menos nessas tarefas e mais nas aplicações e clientes.

---

### 6. Tenha alcance global em minutos
- O espaço global da nuvem AWS para implantação rápida de aplicações para clientes em todo o mundo, ao mesmo tempo em que oferece baixa latência.
- É possível replicar uma aplicação em outro país em questão de minutos, por exemplo

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
<img width="958" height="490" alt="image" src="https://github.com/user-attachments/assets/7692769e-e1d8-43c5-88e7-0e995cd98840" />

- Data centers isolados dentro de uma região
- Cada data center fica a dezena de quilômetros de distância dos outros. Esta distância entre eles é:
  - Pequena o suficiente para ter alta disponibilidade e baixa latência (ordem de milissegundos)
  - Grande o suficiente para reduzir a chance de um desastre (por exemplo, terremoto destrói data center) afetar diversas AZs

---

### 🌐 Pontos de presença (Edge Locations)
- Usadas para rede de entrega de conteúdo (CDN): armazenar em cache um cópia dos dados para ficar mais perto de uma região específica
- A CDN da AWS é a CloudFront
- Aproximam conteúdo do usuário final, diminuindo a latência e oferecendo uma alta velocidade de transferência

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

## ⚡ Serverless (Computação sem servidor)

Serverless é um modelo de computação onde você **não precisa gerenciar servidores**. A AWS cuida automaticamente da infraestrutura, escalabilidade e disponibilidade.

Você foca apenas no código e na lógica da aplicação.

### 🎯 Características
- Execução sob demanda
- Escala automática (elasticidade total)
- Alta disponibilidade nativa
- Cobrança por execução (pay-per-use)

### 📌 Exemplo
- AWS Lambda

### 🧠 Quando usar
- APIs leves
- Processamento de eventos
- Automações
- Workloads intermitentes

### ⚠️ Limitações
- Tempo máximo de execução
- Menor controle do ambiente
- Pode ter *cold start*

👉 Serverless é ideal quando você quer **simplicidade e escalabilidade sem gerenciar infraestrutura**

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

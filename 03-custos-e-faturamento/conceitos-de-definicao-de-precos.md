# 💡 Conceitos de Definição de Preços na AWS

## 📌 O que é

A definição de preços na AWS refere-se aos **princípios e modelos utilizados para cobrar pelo uso dos serviços**.

O objetivo é oferecer **flexibilidade, escalabilidade e otimização de custos**, permitindo que você pague apenas pelo que realmente utiliza.

---

## 🎯 Quando entender isso é importante

- Planejar custos antes de usar serviços
- Escolher o modelo de cobrança adequado
- Otimizar gastos na nuvem
- Evitar surpresas na fatura

---

## ⚙️ Princípios de precificação

### 💳 Pague pelo que usar (Pay-as-you-go)
- Pague apenas pela quantidade de recursos que usar
- Sem custos iniciais
- Sem contratos obrigatórios

---

### 📉 Economize conforme escala
- Quanto mais você usa, menor o custo por unidade em alguns serviços
- O custo por unidade é incrementalmente menor com o aumento do uso.
- Exemplo:
  - Quanto mais espaço de armazenamento do Amazon S3 você usar, menos pagará por GB

---

### 🔄 Reserve e pague menos
- Alguns serviços oferecem opções de reserva com desconto significativo em comparação com as definições de preços da instância sob demanda
- Menos flexibilidade, mais barato
- Exemplo:
  - Empresa usa instâncias do Amazon EC2 para uma carga de trabalho que precisa ser executada continuamente
  - Executando essa carga de trabalho no Amazon EC2 Instance Savings Plans, pode haver uma economia de até 72% em relação à capacidade equivalente da instância sob demanda

---

## 🧮 Calculadora de preços da AWS (AWS Pricing Calculator)

### 📌 O que é

A **AWS Pricing Calculator** é uma ferramenta que permite **estimar custos antes de utilizar serviços da AWS**.

---

### 🎯 Para que serve

- Simular arquitetura
- Prever custos mensais
- Comparar cenários
- Planejar orçamento

---

### ⚙️ Como funciona

- Você seleciona os serviços
- Configura recursos (CPU, memória, armazenamento)
- Recebe uma estimativa de custo
- É possível também organizar as estimativas da AWS por grupos.
  - Depois de criar a estimativa, pode salvá-la e gerar um link para compartilhá-la com outras pessoas
  <img width="920" height="419" alt="image" src="https://github.com/user-attachments/assets/4cb4e56c-3992-4530-bb78-765b9a520689" />


---

## 📦 Exemplos de definição de preços por serviço

### 🖥️ Amazon EC2
- Cobrança baseada em:
  - Tipo de instância (CPU, memória)
  - Tempo de execução (por segundo ou hora)
  - Região
  - Modelo de pricing (On-Demand, Reserved, Spot)
- É possível economizar ainda mais no Amazon EC2 considerando o Savings Plans e as instâncias reservadas

👉 Exemplo:
<img width="683" height="227" alt="image" src="https://github.com/user-attachments/assets/8585fdc3-13c7-491b-80bd-09b90a770573" />
- Instância do Amazon EC2 implantada na Região Virgínia do Norte
  - Ficou em execução por aproximadamente 107 horas
  - Cerca de 11 GB de espaço de armazenamento do Amazon EBS provisionado no mês
  - Um Application Load Balancer usado por 268 horas
- Neste exemplo, os valores de uso estão abaixo dos limites no nível gratuito da AWS
  - Portanto, o proprietário da conta não teria que pagar por nenhum uso do Amazon EC2 este mês.

---

### ⚡ AWS Lambda
- Permite um milhão de solicitações gratuitas e até 3,2 milhões de segundos de tempo de computação por mês.
- Cobrança baseada em:
  - Número de execuções
  - Tempo de execução (em milissegundos)
  - Memória alocada
- É possível economizar nos custos do AWS Lambda cadastrando-se em um Compute Savings Plan.
  - Um Compute Savings Plan oferece custos de computação mais baixos em troca do compromisso com uma quantidade consistente de uso durante um período de um ou três anos
  - Este é um exemplo de “reserve e pague menos”. 

👉 Exemplo:
<img width="688" height="175" alt="image" src="https://github.com/user-attachments/assets/8e646809-dc5f-4b32-ba19-25a39697258b" />
- Uso do AWS Lambda ocorre na Região Virgínia do Norte
- Fatura lista encargos separados para o número de solicitações de funções e sua duração
 - Havia 680 solicitações para uma função, e a função foi executada por cerca de 255 segundos.
- Tanto o número de solicitações quanto a duração total das solicitações neste exemplo estão abaixo dos limites no nível gratuito da AWS
 - Portanto, o proprietário da conta não precisaria pagar por qualquer uso do AWS Lambda neste mês.

---

### 🪣 Amazon S3
- Cobrança baseada em:
  - Armazenamento
    - Paga apenas pelo armazenamento usado.
    - A taxa de armazenamento é cobrada com base nos tamanhos, storage classes e quanto tempo armazenou cada objeto durante o mês
  - Solicitações e recuperações de dados
    - Paga por solicitações feitas aos seus objetos e buckets do Amazon S3.
    - Por exemplo, suponha que você esteja armazenando arquivos de fotos em buckets do Amazon S3 e hospedando-os em um site. Toda vez que um visitante solicita o site que contém esses arquivos de fotos, isso conta para solicitações que você precisa pagar.
  - Transferência de dados
    - Não há custo de transferência:
      - Entre diferentes buckets do Amazon S3 ou do Amazon S3 para outros serviços dentro da mesma Região AWS
      - Para os dados transferidos para o Amazon S3 da internet ou para o Amazon CloudFront
      - Para os dados transferidos para uma instância do Amazon EC2 na mesma Região AWS que o bucket do Amazon S3
    - No entanto, você paga pelos dados que transfere para dentro e para fora do Amazon S3, com algumas exceções
  - Gerenciamento e replicação:
    - Paga pelos recursos de gerenciamento de armazenamento que ativou nos buckets do Amazon S3 da sua conta
    - Esses recursos incluem inventário, análise e marcação de objetos do Amazon S3.

👉 Exemplo:
<img width="674" height="335" alt="image" src="https://github.com/user-attachments/assets/c95fd3d9-e685-4367-b3be-1606e63f1c29" />

- Usou o Amazon S3 em duas Regiões: Virgínia do Norte e Ohio
  - Em cada Região, as cobranças de cada item baseiam-se nos seguintes fatores:
    - Número de solicitações para adicionar ou copiar objetos em um bucket (esses comandos também são conhecidos como PUT, COPY, POST ou LIST)
    - Número de solicitações para recuperar objetos de um bucket (esse comando também é conhecido como GET)
    - Quantidade de espaço de armazenamento usada
  - A Região Virgínia do Norte tem dois níveis do Amazon S3: Nível 1 e Nível 2
    - No Nível 1: 185 solicitações para adicionar ou copiar objetos em um bucket. Foi usado 0,159 GB de espaço de armazenamento
    - No Nível 2: 923 solicitações para recuperar objetos de um bucket
  - A Região de Ohio tem um nível do Amazon S3: Nível 2
    - Havia quatro solicitações para recuperar objetos de um bucket e 0,000001 GB de espaço de armazenamento foi usado
- Todo o uso do Amazon S3 neste exemplo está abaixo dos limites de nível gratuito da AWS
  - Portanto, o proprietário da conta não teria que pagar por qualquer uso do Amazon S3 neste mês.

---

### 📡 Transferência de dados (Data Transfer)
- Entrada de dados → geralmente gratuita
- Saída de dados → cobrada

---

## 💸 Fatores gerais de custo

- Região (preços variam)
- Tipo de serviço
- Volume de uso
- Tempo de execução
- Transferência de dados

---

## 🚀 Boas práticas

- Usar a AWS Pricing Calculator antes de implementar
- Escolher o modelo de pricing adequado
- Monitorar constantemente o uso
- Desligar recursos não utilizados
- Usar Auto Scaling

---

## ⚖️ Comparações importantes

### EC2 vs Lambda

| EC2 | Lambda |
|-----|--------|
| Cobra por tempo ligado | Cobra por execução |
| Gerenciamento manual | Serverless |
| Ideal para carga contínua | Ideal para eventos |

---

### S3 vs EBS

| S3 | EBS |
|----|-----|
| Armazenamento de objetos | Armazenamento em bloco |
| Cobrança por uso e requisições | Cobrança por volume provisionado |
| Alta durabilidade | Baixa latência |

---

## 🧠 Conceitos importantes para prova

- Pay-as-you-go é o modelo base
- Lambda cobra por execução
- EC2 cobra por tempo de uso
- S3 cobra por armazenamento e requisições
- Data transfer (saída) é cobrado
- Pricing Calculator estima custos

---

## ⚠️ Pegadinhas comuns

- Esquecer custo de transferência de dados
- Achar que desligar EC2 remove todos os custos
- Ignorar custo de requisições no S3
- Não estimar custos antes de usar

---

## 🔁 Resumo rápido

- AWS cobra por uso real
- Cada serviço tem modelo específico
- Lambda = execução
- EC2 = tempo
- S3 = armazenamento + requisições
- Calculator ajuda a prever custos

---

## 📌 Status de aprendizado

- [ ] Entendo os princípios de precificação
- [ ] Sei usar a Pricing Calculator
- [ ] Entendo como EC2, Lambda e S3 são cobrados
- [ ] Sei fatores que impactam custo

# ❄️ AWS Snow Family

## 📌 O que é

A AWS Snow Family é um conjunto de dispositivos físicos fornecidos pela AWS para **transferência de grandes volumes (ordem de exabytes) de dados e processamento em locais sem conectividade adequada com a nuvem**.

Ela é usada principalmente em cenários de **migração de dados e edge computing**. Tanto para dentro quanto para fora da AWS.

---

## 🎯 Quando usar

- Transferir grandes volumes de dados (TBs ou PBs)
- Conexão de internet limitada ou instável
- Ambientes remotos (ex: fábricas, navios, áreas rurais)
- Processamento local (edge computing)

---

## ⚙️ Como funciona

1. Você solicita o dispositivo pela AWS
2. A AWS envia o equipamento físico
3. Você carrega os dados localmente
4. Envia de volta para a AWS
5. Os dados são transferidos para a nuvem

👉 Alternativa à transferência via internet

---

## 📦 Serviços da Snow Family
<img width="917" height="285" alt="image" src="https://github.com/user-attachments/assets/f8709d39-b4b4-49df-ae3b-e72ba655166e" />

### 📀 Snowcone
- Dispositivo pequeno e portátil
- Ideal para ambientes extremos ou com pouco espaço
- Transferência de dados e computação de borda
- Tem 2 CPUs, 4 GB de memória e até 14 TB de armazenamento utilizável
- Pode fazer:
  - Transferência de dados
  - Processamento leve (EC2, Lambda)

📌 Quando usar:
- Mobilidade
- Locais remotos

---

### 📦 Snowball
- Dispositivo intermediário
- Mais capacidade de armazenamento

Tipos:
- **Storage Optimized**
  - Ideais para migrações de dados de grande escala e fluxos de trabalho de transferência recorrentes
  - Armazenamento: 80 TB de capacidade de disco rígido (HDD) para volumes de blocos e armazenamento de objeto compatível com o Amazon S3, além de unidade de estado sólido (SSD) do SATA de 1 TB para volumes de blocos
  - Computação: 40 vCPUs e 80 GiB de memória para dar suporte a instâncias sbe1 do Amazon EC2 (equivalente a C5).
- **Compute Optimized**
  - Fornece recursos de computação poderosos, ideal para atividades como machine learning, análise de vídeo em movimento completo, análise e pilhas de computação locais
  - Armazenamento: capacidade de HDD utilizável de 80 TB para armazenamento de objeto compatível com o Amazon S3 ou volumes de blocos compatíveis com o Amazon EBS e também 28 TB de capacidade de SSD NVMe utilizável para volumes de blocos compatíveis com o Amazon EBS
  - Computação: 104 vCPUs, 416 GiB de memória e uma GPU NVIDIA Tesla V100 opcional. Os dispositivos executam as instâncias sbe-c e sbe-g do Amazon EC2, que são equivalentes às instâncias C5, M5a, G3 e P3.

📌 Quando usar:
- Migração de grandes volumes de dados
- Processamento local

---

### 🏢 Snowmobile
- Caminhão físico de armazenamento
- Capacidade de **exabytes (EB)**

📌 Quando usar:
- Migração massiva de data centers

---

## 🧠 Conceitos importantes

### 🚚 Transferência offline
- Evita uso da internet
- Mais rápido para grandes volumes

---

### 🌐 Edge Computing
- Processamento próximo da origem dos dados
- Reduz latência

---

### 🔐 Segurança
- Criptografia automática
- Proteção física do dispositivo, monitoramento, controle de temperatura e transporte
- Controle via IAM

---

## ⚖️ Comparações importantes

### Snow Family vs Transferência via internet

| Snow Family | Internet |
|------------|----------|
| Muito rápido para grandes volumes | Limitado pela banda |
| Offline | Online |
| Mais seguro fisicamente | Depende da rede |

---

### Snowcone vs Snowball vs Snowmobile

| Serviço | Tamanho | Uso |
|--------|--------|-----|
| Snowcone | Pequeno | Mobilidade |
| Snowball | Médio | Migração de dados |
| Snowmobile | Gigante | Data centers |

---

## 🚀 Benefícios

- Transferência eficiente de grandes volumes
- Funciona sem internet confiável
- Permite processamento local
- Alta segurança

---

## 🧠 Conceitos importantes para prova

- Snow Family = transferência de dados offline
- Inclui Snowcone, Snowball e Snowmobile
- Usado para grandes volumes de dados
- Pode fazer edge computing

---

## ⚠️ Pegadinhas comuns

- Achar que é serviço online (não é)
- Confundir com S3 ou transferência via rede
- Esquecer que pode processar dados (não só transferir)
- Não saber diferença entre Snowcone, Snowball e Snowmobile

---

## 🔁 Resumo rápido

- Snow Family = dispositivos físicos da AWS
- Transferência de dados offline
- Ideal para grandes volumes
- Inclui Snowcone, Snowball e Snowmobile

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Snow Family
- [ ] Sei quando usar
- [ ] Conheço Snowcone, Snowball e Snowmobile
- [ ] Entendo edge computing

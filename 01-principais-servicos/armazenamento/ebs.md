# 💾 EBS (Elastic Block Store)

## 📌 O que é

O EBS (Elastic Block Store) é um serviço de armazenamento em bloco da AWS, usado principalmente com instâncias EC2.

Funciona como um **disco rígido virtual**, onde você pode armazenar dados de forma persistente.

---

## 🎯 Quando usar

- Sistemas operacionais (boot de instâncias EC2)
- Bancos de dados
- Aplicações que exigem baixa latência
- Armazenamento que precisa ser persistente

---

## ⚙️ Como funciona

- Você cria um volume EBS
- Anexa esse volume a uma instância EC2
- O sistema operacional enxerga como um disco

---

## 📦 Conceitos importantes

### 📀 Volume EBS
- Unidade de armazenamento
- Pode ser criada, anexada, destacada e reutilizada

---

### 🔗 Anexação
- Volume deve estar na mesma AZ da instância
- Pode ser anexado a uma instância por vez (na maioria dos casos)

---

### 💾 Persistência
- Dados permanecem mesmo se a instância for parada
- Diferente de armazenamento temporário (Instance Store)

---

### 📸 Snapshots
- Backups do volume EBS
- Armazenados no S3
- Permitem restaurar dados ou criar novos volumes

---

## ⚙️ Tipos de volume (visão geral)

- SSD (uso geral e alto desempenho)
- HDD (armazenamento de baixo custo)

👉 Cada tipo varia em:
- Performance
- Custo
- Uso recomendado

---

## 💰 Modelo de cobrança

Você paga por:
- Espaço provisionado (GB)
- Tipo de volume
- Snapshots armazenados

👉 Mesmo sem uso ativo, o volume continua sendo cobrado

---

## 🔒 Segurança

- Criptografia suportada (em repouso)
- Controle via IAM
- Pode ser integrado com KMS (Key Management Service)

---

## ⚖️ Comparações importantes

### EBS vs S3

| EBS | S3 |
|-----|----|
| Armazenamento em bloco | Armazenamento de objetos |
| Baixa latência | Alta escalabilidade |
| Precisa de EC2 | Acesso via HTTP |

---

### EBS vs Instance Store

| EBS | Instance Store |
|-----|----------------|
| Persistente | Temporário |
| Pode ser reutilizado | Dados são perdidos ao parar instância |
| Backup com snapshot | Sem backup nativo |

---

## 🧠 Conceitos importantes para prova

- EBS = armazenamento em bloco
- Usado com EC2
- Dados persistem após parada da instância
- Snapshots são armazenados no S3
- Volume deve estar na mesma AZ da instância

---

## ⚠️ Pegadinhas comuns

- EBS ≠ S3 (bloco vs objeto)
- Não é acessível via internet diretamente
- Continua cobrando mesmo sem uso ativo
- Geralmente não pode ser compartilhado entre múltiplas instâncias

---

## 🔁 Resumo rápido

- EBS = disco virtual para EC2
- Armazenamento persistente e de baixa latência
- Suporte a backup via snapshots
- Cobrança por armazenamento provisionado

---

## 📌 Status de aprendizado

- [ ] Entendo o que é EBS
- [ ] Sei quando usar
- [ ] Entendo snapshots
- [ ] Sei diferença entre EBS, S3 e Instance Store

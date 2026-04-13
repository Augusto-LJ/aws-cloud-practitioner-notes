# 📁 EFS (Elastic File System)

## 📌 O que é

O EFS (Elastic File System) é um serviço de armazenamento de arquivos da AWS.

Ele permite criar um sistema de arquivos compartilhado, que pode ser acessado simultaneamente por múltiplas instâncias EC2.

---

## 🎯 Quando usar

- Compartilhamento de arquivos entre múltiplas instâncias
- Aplicações que precisam de acesso simultâneo aos mesmos dados
- Sistemas legados que utilizam estrutura de arquivos tradicional
- Ambientes com múltiplos servidores (ex: clusters)

---

## ⚙️ Como funciona

- Você cria um sistema de arquivos EFS
- Conecta (mount) em instâncias EC2
- As instâncias acessam como se fosse um diretório local
- Armazena dados em várias Zonas de Disponibilidade e entre elas

---

## 📦 Conceitos importantes

### 📁 Sistema de arquivos
- Estrutura hierárquica (pastas e arquivos)
- Similar ao Windows/Linux

---

### 🔗 Montagem (Mount)
- EFS é montado nas instâncias usando NFS (Network File System)

---

### 🔄 Acesso simultâneo
- Pode ser acessado por várias instâncias ao mesmo tempo
- Ideal para aplicações distribuídas

---

### 📈 Escalabilidade automática
- Cresce e reduz automaticamente conforme uso
- Não precisa provisionar tamanho

---

## 💰 Modelo de cobrança

Você paga por:
- Armazenamento utilizado (GB)

👉 Não precisa provisionar capacidade antecipadamente

---

## 🔒 Segurança

- Controle via IAM
- Integração com Security Groups
- Suporte a criptografia (em repouso e em trânsito)

---

## ⚖️ Comparações importantes

### EFS vs EBS

| EFS | EBS |
|-----|-----|
| Arquivos | Blocos |
| Compartilhado | Uso individual (geralmente) |
| Escala automática | Precisa provisionar |
| Múltiplas instâncias | Uma instância por vez |

---

### EFS vs S3

| EFS | S3 |
|-----|----|
| Sistema de arquivos | Armazenamento de objetos |
| Acesso via NFS | Acesso via HTTP |
| Baixa latência | Alta escalabilidade |
| Uso com EC2 | Uso geral |

---

## 🧠 Conceitos importantes para prova

- EFS = armazenamento de arquivos
- Pode ser acessado por múltiplas instâncias simultaneamente
- Escala automaticamente
- Usa protocolo NFS
- Ideal para sistemas compartilhados

---

## ⚠️ Pegadinhas comuns

- EFS ≠ EBS (arquivo vs bloco)
- EFS não é ideal para bancos de dados de alta performance
- Mais caro que EBS
- Não substitui S3 para armazenamento de objetos

---

## 🔁 Resumo rápido

- EFS = sistema de arquivos compartilhado
- Acesso simultâneo por múltiplas instâncias
- Escalabilidade automática
- Ideal para aplicações distribuídas

---

## 📌 Status de aprendizado

- [ ] Entendo o que é EFS
- [ ] Sei quando usar
- [ ] Entendo acesso simultâneo
- [ ] Sei diferença entre EFS, EBS e S3

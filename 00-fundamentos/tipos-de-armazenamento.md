# 💾 Tipos de Armazenamento

## 📌 O que é

Na computação em nuvem, existem diferentes formas de armazenar dados, cada uma com características específicas e casos de uso ideais.

Os três principais tipos de armazenamento são:
- Armazenamento em bloco
- Armazenamento de objetos
- Armazenamento de arquivos

---

## 🧱 Armazenamento em bloco (Block Storage)

### 📌 O que é
Armazena dados em **blocos**, como se fosse um disco rígido tradicional.

Cada bloco pode ser gerenciado individualmente pelo sistema operacional.

---

### 🎯 Quando usar
- Sistemas operacionais
- Bancos de dados
- Aplicações que exigem baixa latência

---

### 📦 Exemplo na AWS
- EBS (Elastic Block Store)

---

### ⚙️ Características
- Alto desempenho
- Baixa latência
- Precisa ser anexado a uma instância (ex: EC2)

---

## 🗂️ Armazenamento de objetos (Object Storage)

### 📌 O que é
Armazena dados como **objetos**, que incluem:
- Dados (arquivo)
- Metadados
- Chave

---

### 🎯 Quando usar
- Imagens, vídeos e arquivos estáticos
- Backups
- Data lakes

---

### 📦 Exemplo na AWS
- S3 (Simple Storage Service)

---

### ⚙️ Características
- Altamente escalável
- Acesso via HTTP/HTTPS
- Não possui estrutura de diretórios real (simulada)

---

## 📁 Armazenamento de arquivos (File Storage)

### 📌 O que é
Armazena dados em uma estrutura hierárquica de **pastas e arquivos**.

Semelhante a sistemas tradicionais (ex: Windows Explorer).

---

### 🎯 Quando usar
- Compartilhamento de arquivos
- Sistemas que precisam de acesso simultâneo
- Aplicações legadas

---

### 📦 Exemplo na AWS
- EFS (Elastic File System)

---

### ⚙️ Características
- Estrutura de diretórios
- Pode ser acessado por múltiplas instâncias ao mesmo tempo
- Fácil integração com sistemas existentes

---

## ⚖️ Comparação rápida

| Tipo        | Estrutura       | Uso principal              | Exemplo AWS |
|-------------|----------------|---------------------------|------------|
| Bloco       | Blocos         | SO, banco de dados        | EBS        |
| Objetos     | Objetos        | Arquivos, backups         | S3         |
| Arquivos    | Pastas/arquivos| Compartilhamento          | EFS        |

---

## 🧠 Conceitos importantes para prova

- EBS = armazenamento em bloco
- S3 = armazenamento de objetos
- EFS = armazenamento de arquivos
- Cada tipo tem um caso de uso específico

---

## ⚠️ Pegadinhas comuns

- S3 não é armazenamento em bloco
- EBS não pode ser acessado por múltiplas instâncias simultaneamente (em geral)
- EFS não é ideal para bancos de dados de alta performance

---

## 🔁 Resumo rápido

- Bloco → baixo nível, alto desempenho (EBS)
- Objetos → escalável e simples (S3)
- Arquivos → estrutura tradicional (EFS)

---

## 📌 Status de aprendizado

- [ ] Sei diferenciar os 3 tipos de armazenamento
- [ ] Sei quando usar cada um
- [ ] Sei os exemplos na AWS (EBS, S3, EFS)

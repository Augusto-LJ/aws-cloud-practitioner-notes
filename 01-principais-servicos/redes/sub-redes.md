# 🧩 Sub-redes (Subnets)

## 📌 O que são

Uma sub-rede é uma **divisão de uma VPC** onde você pode agrupar recursos.

---

## 🎯 Objetivo

- Organizar recursos
- Isolar componentes
- Controlar acesso

---

## 🔐 Tipos de sub-rede

### 🌐 Sub-rede pública
- Acessível pela internet
- Exemplo:
  - Servidores web

---

### 🔒 Sub-rede privada
- Não acessível diretamente pela internet
- Exemplo:
  - Bancos de dados

---

## 🧠 Analogia
<img width="919" height="533" alt="image" src="https://github.com/user-attachments/assets/f8dc3ae5-b704-4352-bf8b-5c943a6b6176" />

- VPC = cafeteria
- Sub-rede pública = área do caixa
- Sub-rede privada = área do barista

👉 Clientes não acessam diretamente a área privada

---

## 🔄 Comunicação

- Sub-redes podem se comunicar entre si
- Exemplo:
  - EC2 (público) → Banco (privado)

---

## 🧠 Conceitos para prova

- Subnet = divisão da VPC
- Pública vs privada
- Isolamento de recursos

---

## 🔁 Resumo

- Subnet organiza e protege recursos

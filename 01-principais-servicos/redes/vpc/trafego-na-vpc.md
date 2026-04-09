# 📡 Tráfego de rede em uma VPC

## 📌 O que é

Tráfego de rede é o fluxo de dados (pacotes) dentro e fora da VPC.

---

## 📦 Pacote

- Unidade de dados enviada pela rede

---

## ⚙️ Fluxo de tráfego

1. Cliente envia requisição
2. Pacote entra pela internet gateway
3. Passa por verificações de segurança
4. Chega ao recurso

---

## 🔐 Controle de tráfego
<img width="913" height="485" alt="image" src="https://github.com/user-attachments/assets/dbe91bf2-4e20-4d0a-88c0-43748780227a" />

Antes de entrar ou sair:

- ACLs (Lista de controle de acesso ou access control list) verificam sub-rede
- Grupos de segurança (Security Groups) verificam instância

---

## 🧠 Conceitos para prova

- Tráfego = pacotes
- Passa por múltiplas camadas de segurança

---

## 🔁 Resumo

- Tráfego é controlado em vários níveis

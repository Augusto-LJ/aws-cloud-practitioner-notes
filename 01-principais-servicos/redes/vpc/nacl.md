# 🛡️ Network ACL (NACL)

## 📌 O que é

Uma NACL é um firewall virtual que controla tráfego de entrada e saída no **nível de sub-rede**.

---

## ⚙️ Características

- Atua na entrada e saída
- Stateless (não lembra conexões)

---

## 🔄 Stateless

- Cada pacote é analisado separadamente
- Regras precisam existir para entrada e saída

---

## 📜 Regras

- Permitir ou negar tráfego
- Ordem importa
- Existe regra de negação implícita

---

## 🧠 Analogia (aeroporto)

- Viajantes tentam entrar em outro país e passam por um oficial de controle de passaportes
  - Nesse caso, viajantes são pacotes e o oficial de controle de passaportes é uma ACL de rede
- O oficial de controle de passaportes verifica as credenciais dos viajantes quando entram e saem do país.
  - Se um viajante estiver em uma lista aprovada, ele poderá passar.
  - No entanto, se ele não estiver na lista aprovada ou estiver explicitamente em uma lista de viajantes proibidos, ele não poderá entrar. 

---

## ⚖️ Padrão vs customizada

| Tipo | Comportamento |
|------|-------------|
| Default | Permite tudo |
| Custom | Nega tudo até liberar |

---

## 🧠 Conceitos para prova

- NACL = nível subnet
- Stateless
- Regras explícitas

---

## 🔁 Resumo

- NACL controla tráfego da sub-rede

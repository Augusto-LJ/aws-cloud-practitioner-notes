# 🌐 Amazon Route 53

## 📌 O que é

O Amazon Route 53 é um serviço de **DNS (Domain Name System)** altamente disponível e escalável.

Ele traduz nomes de domínio (ex: google.com) em endereços IP.

---

## 🎯 Quando usar

- Registrar domínios
- Gerenciar DNS
- Direcionar tráfego para aplicações
- Implementar alta disponibilidade

---

## ⚙️ Como funciona

- Usuário acessa um domínio
- Route 53 resolve para um IP ou recurso AWS
- Direciona o tráfego corretamente

---

## 📦 Conceitos importantes

### 🌍 Hosted Zone
- Container de registros DNS
- Pode ser:
  - Pública
  - Privada

---

### 📄 Record Sets
- Registros DNS
- Exemplos:
  - A → IP
  - CNAME → outro domínio
  - MX → email

---

### ⏱️ TTL (Time To Live)
- Tempo de cache de um registro DNS

---

## 🎯 Tipos de roteamento

### ⚖️ Simple Routing
- Um único destino

---

### ⚖️ Weighted Routing
- Distribui tráfego por porcentagem

---

### 🌎 Latency Routing
- Direciona para menor latência

---

### ❤️ Health Check Routing
- Só envia tráfego para recursos saudáveis

---

### 🌐 Geolocation Routing
- Baseado na localização do usuário

---

### 🔁 Failover Routing
- Alta disponibilidade (primary → secondary)

---

## 🔍 Health Checks

- Monitoram recursos (ex: EC2, endpoints)
- Permitem failover automático

---

## 🚀 Casos de uso

- Balanceamento de carga global
- Failover entre regiões
- Redirecionamento de domínios

---

## 💰 Benefícios

- Alta disponibilidade
- Escalabilidade global
- Integração com AWS
- Diversos tipos de roteamento

---

## ⚖️ Comparações importantes

### Route 53 vs DNS tradicional

| Route 53 | DNS tradicional |
|----------|----------------|
| Integrado AWS | Genérico |
| Health checks | Limitado |
| Roteamento avançado | Básico |

---

## 🧠 Conceitos importantes para prova

- Route 53 é DNS
- Suporta múltiplos tipos de roteamento
- Permite health checks
- Alta disponibilidade

---

## ⚠️ Pegadinhas comuns

- Confundir com load balancer
- Achar que ele armazena conteúdo (não armazena)
- Não entender diferença entre tipos de routing

---

## 🔁 Resumo rápido

- Route 53 = DNS da AWS
- Resolve domínios para recursos
- Suporte a roteamento avançado

---

## 📌 Status de aprendizado

- [ ] Entendo o que é DNS
- [ ] Sei o que é Hosted Zone
- [ ] Conheço tipos de routing
- [ ] Entendo Health Checks

# 🛡️ WAF (Web Application Firewall)

## 📌 O que é

O AWS WAF (Web Application Firewall) é um serviço que protege aplicações web contra **ataques comuns na camada HTTP/HTTPS**.

Ele filtra e monitora o tráfego com base em regras definidas.

---

## 🎯 Quando usar

- Proteger APIs e aplicações web
- Bloquear ataques comuns (ex: SQL Injection, XSS)
- Controlar acesso por IP, país ou padrão de requisição

---

## ⚙️ Como funciona

- Você define regras (rules)
- O WAF analisa requisições HTTP/HTTPS
- Permite ou bloqueia o tráfego com base nessas regras

---

## 📦 Conceitos importantes

### 📜 Web ACL (Access Control List)
- Conjunto de regras aplicadas a um recurso
- Define o que é permitido ou bloqueado

---

### 🧩 Regras (Rules)
- Condições para analisar requisições
- Exemplo:
  - Bloquear IP específico
  - Bloquear padrão suspeito

---

### 📦 Rule Groups
- Conjunto de regras reutilizáveis
- Pode ser gerenciado pela AWS ou customizado

---

## 🔍 Tipos de proteção

- SQL Injection
- Cross-Site Scripting (XSS)
- Bots maliciosos
- Tráfego de IPs suspeitos

---

## 🔗 Integrações

O WAF pode ser usado com:

- CloudFront
- Application Load Balancer (ALB)
- API Gateway

---

## 💰 Modelo de cobrança

Você paga por:
- Web ACLs
- Número de regras
- Volume de requisições analisadas

---

## 🔒 Segurança

- Atua na camada de aplicação (Layer 7)
- Complementa outros serviços como Security Groups

---

## ⚖️ Comparações importantes

### WAF vs Security Group

| WAF | Security Group |
|-----|---------------|
| Camada HTTP/HTTPS | Camada de rede (porta/IP) |
| Filtra requisições web | Controla tráfego de rede |
| Mais inteligente | Mais básico |

---

### WAF vs Shield

| WAF | Shield |
|-----|--------|
| Protege contra ataques web | Protege contra DDoS |
| Regras customizadas | Proteção automática |

---

## 🧠 Conceitos importantes para prova

- WAF protege aplicações web
- Atua na camada HTTP/HTTPS
- Usa regras para filtrar tráfego
- Integra com CloudFront, ALB e API Gateway

---

## ⚠️ Pegadinhas comuns

- WAF não substitui Security Groups
- Não protege contra todos os tipos de ataque
- Atua apenas na camada de aplicação
- Não é focado exclusivamente em DDoS

---

## 🔁 Resumo rápido

- WAF = firewall para aplicações web
- Protege contra ataques comuns (SQLi, XSS)
- Baseado em regras
- Atua na camada HTTP/HTTPS

---

## 📌 Status de aprendizado

- [ ] Entendo o que é WAF
- [ ] Sei quando usar
- [ ] Entendo diferença para Security Groups
- [ ] Sei quais ataques ele protege

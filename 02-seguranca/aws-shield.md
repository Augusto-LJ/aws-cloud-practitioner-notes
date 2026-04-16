# 🛡️ AWS Shield

## 📌 O que é

O AWS Shield é um serviço de proteção contra ataques **DDoS (Distributed Denial of Service)**.

Ele protege automaticamente aplicações e infraestrutura contra tentativas de sobrecarga de tráfego malicioso.

---

---
## 📦 Conceitos importantes

### 👨‍💻 Ataques Denial of Service (DoS)
- É uma tentativa deliberada de tornar um site ou aplicação indisponível para os usuários.
- O ataque se origina de uma fonte única
<img width="525" height="555" alt="image" src="https://github.com/user-attachments/assets/99c2357e-54e8-4de8-a5f7-5a9818446c51" />


### 👨‍💻 Ataques Distributed Denial of Service (DDoS)
- Têm como objetivo **tornar uma aplicação indisponível**, sobrecarregando-a com um grande volume de requisições.
- Diferentemente do DoS, este tipo de ataque é distribuído. Ou seja, o ataque tem origem de várias fontes
 - Pode ser feito por vários invasores ou por um invasor utilizando "computadores infectados" (ou bots)
<img width="530" height="388" alt="image" src="https://github.com/user-attachments/assets/2a3f7efc-96dc-4e58-84bd-53a57b5072f8" />

#### 📦 Principais tipos de ataques DDoS

#### 🌊 UDP Flood (Layer 4)
- Envio massivo de pacotes UDP
- Consome largura de banda e recursos da rede

---

#### 🌐 SYN Flood (Layer 4)
- Explora o processo de handshake TCP
- Abre várias conexões sem finalizá-las

---

#### 🐌 Slowloris (Layer 7)
- Envia requisições HTTP muito lentas
- Mantém conexões abertas por longos períodos
- Consome recursos do servidor

---

#### 🌍 HTTP Flood (Layer 7)
- Grande volume de requisições HTTP legítimas
- Difícil de diferenciar de usuários reais

---

## 🎯 Quando usar AWS Shield

- Proteger aplicações públicas na internet
- Evitar indisponibilidade causada por ataques DDoS
- Garantir disponibilidade de sistemas críticos

---

## ⚙️ Como funciona

- Monitora o tráfego da aplicação
- Detecta padrões de ataque DDoS
- Mitiga automaticamente o tráfego malicioso

---

## 📦 Tipos de AWS Shield

### 🟢 Shield Standard
- Ativado automaticamente (sem custo adicional)
- Proteção básica contra DDoS
- Protege serviços como:
  - CloudFront
  - Route 53
  - ELB

---

### 🔵 Shield Advanced
- Versão paga
- Proteção mais sofisticada
- Inclui:
  - Monitoramento detalhado
  - Resposta avançada a incidentes
  - Suporte da AWS (DDoS Response Team)
  - Integração com outros serviços, como Amazon CloudFront, Amazon Route 53, Elastic Load Balancing e AWS WAF

---

## 🔐 Outras formas de proteção na AWS

Além do Shield, outros serviços ajudam na defesa contra DDoS:

### 🔒 Security Groups
- Filtram tráfego por IP, porta e protocolo
- Atuam no nível da instância (EC2)

---

### 🛡️ Network ACL (NACL)
- Controle de tráfego no nível da sub-rede
- Pode bloquear IPs maliciosos

---

### 🌐 AWS WAF
- Protege contra ataques na camada de aplicação (HTTP/HTTPS)
- Mitiga ataques como:
  - HTTP Flood
  - SQL Injection
  - XSS

---

### 🚀 CloudFront
- Absorve grandes volumes de tráfego
- Distribui carga globalmente (CDN)
- Ajuda a mitigar ataques volumétricos

---

## 🔒 Segurança

- Atua principalmente na **camada de rede (Layer 3 e 4)**
- Focado em manter disponibilidade
- Proteção automática (especialmente no Standard)

---

## ⚖️ Comparações importantes

### AWS Shield vs WAF

| AWS Shield | WAF |
|------------|-----|
| Protege contra DDoS | Protege contra ataques web |
| Camada de rede (L3/L4) | Camada de aplicação (L7) |
| Atua no volume de tráfego | Analisa conteúdo das requisições |
| Automático | Baseado em regras |

👉 Resumindo:
- **Shield → protege contra sobrecarga (volume de tráfego)**
- **WAF → protege contra ataques na aplicação (ex: SQL Injection)**

---

### Shield Standard vs Advanced

| Standard | Advanced |
|----------|----------|
| Gratuito | Pago |
| Proteção básica | Proteção avançada |
| Automático | Monitoramento e suporte adicional |

---

## 🧠 Conceitos importantes para prova

- DDoS = sobrecarga de tráfego
- Shield protege contra ataques volumétricos
- Shield Standard já vem ativado
- WAF protege camada de aplicação (L7)
- CloudFront ajuda a absorver ataques
- Defesa em camadas é essencial

---

## ⚠️ Pegadinhas comuns

- Confundir Shield com WAF
- Achar que Shield protege contra SQL Injection (não protege)
- Esquecer que Shield Standard já está ativo
- Pensar que apenas um serviço resolve tudo (é defesa em camadas)

---

## 🔁 Resumo rápido

- DDoS = ataque de sobrecarga
- Shield = proteção principal contra DDoS
- WAF = proteção na aplicação
- CloudFront + Shield + WAF = proteção completa

---

## 📌 Status de aprendizado

- [ ] Entendo o que é DDoS
- [ ] Conheço tipos de ataques (UDP, SYN, HTTP, Slowloris)
- [ ] Sei como AWS Shield atua
- [ ] Entendo proteção em camadas na AWS

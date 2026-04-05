# 🛡️ AWS Shield

## 📌 O que é

O AWS Shield é um serviço de proteção contra ataques **DDoS (Distributed Denial of Service)**.

Ele protege automaticamente aplicações e infraestrutura contra tentativas de sobrecarga de tráfego malicioso.

---

## 🎯 Quando usar

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

- Shield protege contra DDoS
- Shield Standard já vem ativado
- Atua na camada de rede
- Não substitui o WAF
- Shield + WAF = proteção completa

---

## ⚠️ Pegadinhas comuns

- Confundir Shield com WAF
- Achar que Shield protege contra SQL Injection (não protege)
- Esquecer que Shield Standard já está ativo
- Pensar que WAF protege contra DDoS (não é o foco)

---

## 🔁 Resumo rápido

- Shield = proteção contra DDoS
- Atua automaticamente
- Protege a infraestrutura contra sobrecarga
- Complementa o WAF

---

## 📌 Status de aprendizado

- [ ] Entendo o que é AWS Shield
- [ ] Sei diferença entre Shield e WAF
- [ ] Conheço Shield Standard vs Advanced
- [ ] Entendo como ele protege contra DDoS

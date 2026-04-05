# ⚖️ Elastic Load Balancing (ELB)

## 📌 O que é

O Elastic Load Balancing (ELB) é um serviço que **distribui automaticamente o tráfego de entrada entre múltiplas instâncias** (como EC2).

Ele melhora:
- Disponibilidade
- Escalabilidade
- Tolerância a falhas

---

## 🎯 Quando usar

- Aplicações com múltiplas instâncias
- Sistemas que precisam de alta disponibilidade
- Distribuição de carga entre servidores

---

## ⚙️ Como funciona

- O ELB recebe requisições dos usuários
- Distribui o tráfego entre múltiplos targets (instâncias)
- Remove automaticamente instâncias com falha

---

## 📦 Tipos de Load Balancer

### 🌐 Application Load Balancer (ALB)
- Camada 7 (HTTP/HTTPS)
- Roteamento baseado em:
  - URL
  - Host (domínio)
- Ideal para aplicações web

---

### 🚀 Network Load Balancer (NLB)
- Camada 4 (TCP/UDP)
- Alta performance e baixa latência
- Ideal para tráfego em grande escala

---

### 🏢 Classic Load Balancer (CLB)
- Versão antiga
- Suporte limitado
- Não recomendado para novos projetos

---

## 🔗 Componentes importantes

### 🎯 Target Group
- Grupo de recursos que recebem tráfego
- Pode conter:
  - EC2
  - Containers
  - IPs

---

### ❤️ Health Checks
- Verifica se instâncias estão saudáveis
- Remove automaticamente instâncias com problema

---

### 🌍 Availability Zones
- Distribui tráfego entre múltiplas zonas
- Aumenta disponibilidade

---

## 🔄 Integrações

- Auto Scaling → adiciona/remove instâncias automaticamente
- CloudWatch → monitora métricas
- WAF → proteção contra ataques web

---

## 🚀 Casos de uso

- Balancear tráfego de aplicações web
- Alta disponibilidade entre múltiplas AZs
- Distribuição de carga em APIs

---

## 💰 Benefícios

- Alta disponibilidade
- Escalabilidade automática
- Tolerância a falhas
- Distribuição inteligente de tráfego

---

## ⚖️ Comparações importantes

### ALB vs NLB

| ALB | NLB |
|-----|-----|
| HTTP/HTTPS | TCP/UDP |
| Camada 7 | Camada 4 |
| Mais inteligente | Mais rápido |
| Roteamento avançado | Alta performance |

---

### ELB vs Auto Scaling

| ELB | Auto Scaling |
|-----|--------------|
| Distribui tráfego | Ajusta quantidade de instâncias |
| Atua no balanceamento | Atua na capacidade |
| Trabalha junto com ASG | Usa ELB para distribuir carga |

---

## 🧠 Conceitos importantes para prova

- ELB distribui tráfego entre instâncias
- ALB (camada 7) e NLB (camada 4)
- Usa health checks
- Integra com Auto Scaling

---

## ⚠️ Pegadinhas comuns

- Confundir ELB com Auto Scaling
- Escolher tipo errado (ALB vs NLB)
- Ignorar health checks
- Não usar múltiplas AZs

---

## 🔁 Resumo rápido

- ELB = balanceador de carga
- Distribui requisições
- Aumenta disponibilidade
- Trabalha junto com Auto Scaling

---

## 📌 Status de aprendizado

- [ ] Entendo o que é ELB
- [ ] Sei diferença entre ALB e NLB
- [ ] Entendo health checks
- [ ] Sei como integra com Auto Scaling

# 📊 CloudWatch

## 📌 O que é

O Amazon CloudWatch é um serviço de **monitoramento e observabilidade** da AWS.

Ele coleta e exibe métricas, logs e eventos para acompanhar o funcionamento dos recursos e aplicações.

---

## 🎯 Quando usar

- Monitorar performance de serviços (EC2, RDS, etc.)
- Criar alertas automáticos
- Analisar logs de aplicações
- Automatizar ações com base em eventos

---

## ⚙️ Como funciona

- Serviços AWS enviam métricas automaticamente
- Você pode enviar métricas customizadas
- O CloudWatch armazena logs e dados
- Com base nesses dados, você pode criar alarmes e ações

---

## 📦 Conceitos importantes

### 📈 Métricas (Metrics)
- Dados numéricos ao longo do tempo
- Exemplos:
  - Uso de CPU
  - Latência
  - Número de requisições

---

### 🧾 Logs (CloudWatch Logs)
- Armazena logs de aplicações e serviços
- Permite busca e análise

---

### ⏰ Alarmes (Alarms)
- Disparam ações com base em condições
- Exemplo:
  - CPU > 80% → enviar alerta

---

### ⚡ Eventos (Events / EventBridge)
- Reage a eventos da AWS
- Permite automação baseada em ações

---

### 📊 Dashboards
- Painéis visuais com métricas
- Ajuda a visualizar o estado do sistema

---

## 🔄 Integrações comuns

- EC2 → monitoramento de CPU, rede
- RDS → monitoramento de banco
- Lambda → métricas de execução
- Auto Scaling → escala baseado em métricas

---

## 🚀 Casos de uso

- Escalar instâncias automaticamente
- Detectar falhas rapidamente
- Monitorar aplicações em produção
- Criar alertas operacionais

---

## 💰 Modelo de cobrança

Você paga por:
- Métricas customizadas
- Logs armazenados
- Alarmes configurados
- Dashboards adicionais

(Métricas básicas de alguns serviços são gratuitas)

---

## ⚖️ Comparações importantes

### CloudWatch vs CloudTrail

| CloudWatch | CloudTrail |
|------------|------------|
| Monitoramento e métricas | Auditoria de ações |
| Foco em performance | Foco em segurança |
| Dados em tempo real | Histórico de eventos |

---

## 🧠 Conceitos importantes para prova

- CloudWatch monitora métricas e logs
- Permite criação de alarmes
- Integra com Auto Scaling
- Suporta métricas customizadas

---

## ⚠️ Pegadinhas comuns

- Confundir CloudWatch com CloudTrail
- Achar que logs são automáticos para tudo (nem sempre)
- Não configurar alarmes (monitorar sem agir)

---

## 🔁 Resumo rápido

- CloudWatch = monitoramento
- Coleta métricas e logs
- Cria alertas e automações
- Essencial para observabilidade

---

## 📌 Status de aprendizado

- [ ] Entendo o que é CloudWatch
- [ ] Sei diferença entre métricas e logs
- [ ] Sei configurar alarmes
- [ ] Entendo integração com Auto Scaling

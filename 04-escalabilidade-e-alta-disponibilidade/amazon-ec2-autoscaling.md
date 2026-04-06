# 📈 Amazon EC2 Auto Scaling

## 📌 O que é

O Amazon EC2 Auto Scaling é um serviço que **ajusta automaticamente a quantidade de instâncias EC2** com base na demanda.

Ele garante:
- Escalabilidade automática
- Alta disponibilidade
- Otimização de custos

---

## 🎯 Quando usar

- Aplicações com variação de carga
- Sistemas que precisam de alta disponibilidade
- Redução de custos (desligar recursos ociosos)

---

## ⚙️ Como funciona

- Você define um grupo de Auto Scaling
- Configura regras de escala (scale in / scale out)
- O serviço adiciona ou remove instâncias automaticamente

---

## 📦 Conceitos importantes

### 👥 Auto Scaling Group (ASG)
- Grupo de instâncias EC2
- Define:
  - Mínimo de instâncias
  - Máximo de instâncias
  - Capacidade desejada
    - Se não especificar o número desejado, a capacidade desejada se tornará a capacidade mínima.

---

### 📏 Scaling Policies (Políticas de escala)

#### 🔼 Scale Out (aumentar)
- Adiciona instâncias quando a demanda cresce

#### 🔽 Scale In (reduzir)
- Remove instâncias quando a demanda diminui

---

### ⏱️ Tipos de Scaling

#### 📊 Dynamic Scaling
- Baseado em métricas (ex: CPU)
- Exemplo:
  - CPU > 70% → adiciona instâncias

---

#### ⏰ Scheduled Scaling
- Baseado em horário
- Exemplo:
  - Aumentar instâncias às 9h

---

#### ⚡ Predictive Scaling
- Usa machine learning para prever demanda
- Escala antes do pico acontecer

---

### 📡 Integração com CloudWatch

- CloudWatch fornece métricas
- Auto Scaling usa essas métricas para tomar decisões

---

### 🔁 Health Checks

- Monitora a saúde das instâncias
- Substitui automaticamente instâncias com falha

---

## 🚀 Casos de uso

- Aplicações web com tráfego variável
- APIs com picos de acesso
- Sistemas críticos que não podem ficar fora do ar

---

## 💰 Benefícios

- Redução de custos
- Alta disponibilidade
- Escalabilidade automática
- Menor intervenção manual

---

## ⚖️ Comparações importantes

### Auto Scaling vs Escala manual

| Auto Scaling | Manual |
|--------------|--------|
| Automático | Manual |
| Baseado em métricas | Baseado em decisão humana |
| Rápido | Lento |

---

### Scale Up vs Scale Out

| Scale Up | Scale Out |
|----------|-----------|
| Aumenta capacidade da máquina | Aumenta número de máquinas |
| Vertical | Horizontal |
| Mais limitado | Mais escalável |

---

## 🧠 Conceitos importantes para prova

- Auto Scaling ajusta instâncias automaticamente
- Usa métricas do CloudWatch
- ASG define limites (min, max, desired)
- Substitui instâncias com falha

---

## ⚠️ Pegadinhas comuns

- Confundir scale up com scale out
- Não definir limites corretamente
- Esquecer health checks
- Não integrar com CloudWatch

---

## 🔁 Resumo rápido

- Auto Scaling = ajuste automático de instâncias
- Baseado em demanda
- Usa CloudWatch
- Garante disponibilidade e reduz custos

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Auto Scaling
- [ ] Sei o que é ASG
- [ ] Entendo tipos de scaling
- [ ] Sei como funciona integração com CloudWatch

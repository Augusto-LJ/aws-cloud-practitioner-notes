# 🧠 AWS Trusted Advisor

## 📌 O que é

O AWS Trusted Advisor é uma ferramenta que fornece **recomendações em tempo real** para ajudar a otimizar sua conta AWS.

Ele analisa o ambiente e sugere melhorias em cinco categorias:
- Otimização de custos
- Desempenho
- Segurança
- Tolerância a falhas
- Limites de serviço

---

## 🎯 Quando usar

- Reduzir custos
- Melhorar segurança
- Aumentar performance
- Identificar riscos na infraestrutura

---

## ⚙️ Como funciona

- Analisa os recursos da sua conta AWS
- Compara com boas práticas da AWS
- Exibe recomendações organizadas por categoria

---

## 📊 Painel do AWS Trusted Advisor
<img width="895" height="200" alt="image" src="https://github.com/user-attachments/assets/7c866e92-abc9-4201-b020-5eb31004e054" />

- Exibe informações sobre as 5 categorias citadas
- Para cada categoria:
  - A marca de verificação verde indica o número de itens para os quais nenhum problema foi detectado
  - O triângulo laranja representa o número de investigações recomendadas
  - O círculo vermelho representa o número de ações recomendadas

--- 

## 📦 Categorias de análise

### 💰 Otimização de custos
- Identifica recursos ociosos
- Sugere economia (ex: instâncias não utilizadas)

---

### 🔒 Segurança
- Verifica vulnerabilidades
- Exemplo:
  - Portas abertas
  - MFA não ativado

---

### ⚡ Performance
- Sugere melhorias de desempenho
- Exemplo:
  - Configurações inadequadas

---

### 🛡️ Tolerância a falhas
- Avalia alta disponibilidade
- Exemplo:
  - Recursos não distribuídos em múltiplas AZs

---

### 📊 Limites de serviço
- Monitora uso de limites da AWS
- Evita bloqueios por atingir limites

---

## 🚀 Casos de uso

- Auditoria rápida da infraestrutura
- Redução de custos
- Identificação de riscos
- Melhoria contínua do ambiente

---

## 💰 Disponibilidade por plano

| Plano | Acesso |
|------|--------|
| Basic | Limitado |
| Developer | Limitado |
| Business | Completo |
| Enterprise | Completo |

---

## 🔗 Integrações

- AWS Support → planos pagos ampliam recursos
- CloudWatch → monitoramento complementar
- Cost Explorer → análise de custos detalhada

---

## ⚖️ Comparações importantes

### Trusted Advisor vs Cost Explorer

| Trusted Advisor | Cost Explorer |
|-----------------|---------------|
| Recomenda melhorias | Analisa custos |
| Foco em boas práticas | Foco em gastos |

---

### Trusted Advisor vs CloudWatch

| Trusted Advisor | CloudWatch |
|-----------------|------------|
| Recomendações | Monitoramento |
| Análise periódica | Dados em tempo real |

---

## 🧠 Conceitos importantes para prova

- Trusted Advisor sugere melhorias
- Analisa custos, segurança e performance
- Recursos completos em planos pagos
- Baseado em boas práticas da AWS

---

## ⚠️ Pegadinhas comuns

- Achar que executa mudanças automaticamente (não executa)
- Confundir com CloudWatch
- Ignorar limitações do plano Basic
- Pensar que substitui ferramentas de monitoramento

---

## 🔁 Resumo rápido

- Trusted Advisor = recomendações
- Otimiza custos e segurança
- Baseado em boas práticas
- Não executa ações automaticamente

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Trusted Advisor
- [ ] Sei quais categorias ele analisa
- [ ] Sei diferença para Cost Explorer e CloudWatch
- [ ] Conheço limitações por plano

# 🏢 AWS Outposts

## 📌 O que é

O AWS Outposts é um serviço que permite executar infraestrutura da AWS **dentro do seu data center on-premises**.

Ele leva serviços da AWS para ambientes locais, mantendo integração com a nuvem.

---

## 🎯 Quando usar

- Necessidade de baixa latência com sistemas locais
- Requisitos regulatórios (dados devem ficar on-premises)
- Integração com aplicações legadas
- Cenários híbridos

---

## ⚙️ Como funciona

- A AWS envia racks físicos para sua empresa
- Esses racks contêm hardware gerenciado pela AWS
- Você utiliza serviços AWS localmente como se estivesse na nuvem

---

## 📦 Conceitos importantes

### 🖥️ Infraestrutura gerenciada pela AWS
- Hardware instalado no local
- AWS é responsável por:
  - Manutenção
  - Atualizações
  - Monitoramento

---

### 🌐 Integração com a AWS
- Conectado à região AWS
- Usa mesmas APIs, ferramentas e serviços

---

### 🔄 Extensão da nuvem
- Não é um ambiente separado
- Funciona como uma extensão da AWS

---

## 🔗 Serviços suportados

- EC2
- EBS
- RDS (limitado)
- ECS / EKS (em alguns cenários)

---

## 🚀 Casos de uso

- Aplicações que exigem latência muito baixa
- Processamento local em tempo real
- Indústrias com requisitos regulatórios
- Ambientes híbridos

---

## 💰 Benefícios

- Experiência consistente com AWS
- Baixa latência
- Conformidade regulatória
- Integração com serviços cloud

---

## ⚖️ Comparações importantes

### Outposts vs Região AWS

| Outposts | Região AWS |
|----------|------------|
| On-premises | Nuvem |
| Baixa latência local | Latência de rede |
| Limitado | Completo |

---

### Outposts vs On-premises tradicional

| Outposts | Tradicional |
|----------|-------------|
| Gerenciado pela AWS | Gerenciado pela empresa |
| Integração com cloud | Isolado |
| APIs AWS | Ferramentas próprias |

---

### Outposts vs Local Zones

| Outposts | Local Zones |
|----------|-------------|
| Dentro da empresa | Próximo da empresa |
| Controle local | Infra AWS externa |

---

## 🧠 Conceitos importantes para prova

- Outposts leva AWS para dentro do data center
- Parte de estratégia híbrida
- AWS gerencia infraestrutura
- Integração com região AWS

---

## ⚠️ Pegadinhas comuns

- Achar que substitui a nuvem (não substitui)
- Confundir com região AWS
- Pensar que é totalmente independente da AWS
- Achar que é apenas virtualização (é hardware físico da AWS)

---

## 🔁 Resumo rápido

- Outposts = AWS dentro do seu data center
- Ideal para cenários híbridos
- Baixa latência e compliance

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Outposts
- [ ] Sei quando usar
- [ ] Entendo relação com nuvem híbrida
- [ ] Sei diferença para regiões AWS

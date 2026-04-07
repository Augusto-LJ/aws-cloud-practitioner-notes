# 🚀 Amazon CloudFront

## 📌 O que é

O Amazon CloudFront é um serviço de **CDN (Content Delivery Network)**.

Ele distribui conteúdo com baixa latência através de uma rede global de servidores (edge locations).

---

## 🎯 Quando usar

- Melhorar performance de aplicações web
- Distribuir conteúdo globalmente
- Reduzir latência
- Proteger aplicações

---

## ⚙️ Como funciona

- Usuário faz requisição
- CloudFront entrega conteúdo do edge mais próximo
- Se não estiver em cache, busca na origem

---

## 📦 Conceitos importantes

### 🌍 Edge Locations
- Servidores distribuídos globalmente
- Armazenam conteúdo em cache

---

### 📥 Origin
- Fonte do conteúdo
- Exemplos:
  - S3
  - EC2
  - Load Balancer

---

### 📦 Cache
- Armazena conteúdo para reduzir latência
- Controlado por políticas

---

## 🔐 Segurança

- Integração com AWS Shield (DDoS)
- AWS WAF (firewall)
- HTTPS

---

## 🚀 Casos de uso

- Sites estáticos
- APIs globais
- Streaming de vídeo
- Distribuição de arquivos

---

## 💰 Benefícios

- Baixa latência
- Alta performance
- Distribuição global
- Segurança integrada

---

## ⚖️ Comparações importantes

### CloudFront vs S3 direto

| CloudFront | S3 direto |
|------------|-----------|
| Cache global | Sem cache |
| Mais rápido | Mais lento globalmente |

---

### CloudFront vs ELB

| CloudFront | ELB |
|------------|-----|
| CDN | Load Balancer |
| Cache | Não faz cache |

---

## 🧠 Conceitos importantes para prova

- CloudFront é CDN
- Usa edge locations
- Cache reduz latência
- Pode usar S3 como origin

---

## ⚠️ Pegadinhas comuns

- Confundir com load balancer
- Achar que substitui S3
- Não entender conceito de cache

---

## 🔁 Resumo rápido

- CloudFront = CDN da AWS
- Distribui conteúdo globalmente
- Usa cache para performance

---

## 📌 Status de aprendizado

- [ ] Entendo o que é CDN
- [ ] Sei o que são edge locations
- [ ] Entendo cache
- [ ] Sei quando usar CloudFront

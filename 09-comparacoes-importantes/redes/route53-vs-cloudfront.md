# ⚖️ Route 53 vs CloudFront

## 🔗 Referências

- [Route 53](../../01-principais-servicos/redes/route53.md)
- [CloudFront](../../01-principais-servicos/redes/cloudfront.md)

---

## 📌 Diferença principal (resumo rápido)

- **Route 53** → Serviço de DNS
- **CloudFront** → CDN (distribuição de conteúdo)

---

## ⚖️ Comparação direta

| Route 53 | CloudFront |
|----------|------------|
| DNS | CDN |
| Resolve domínio → IP | Distribui conteúdo |
| Direciona tráfego | Cache de conteúdo |
| Alta disponibilidade | Baixa latência |

---

## 🎯 Quando usar cada um

### Route 53
- Gerenciar domínios
- Direcionar usuários
- Failover e roteamento

---

### CloudFront
- Acelerar entrega de conteúdo
- Cache global
- Reduzir latência

---

## 🧠 Pegadinhas de prova

- Route 53 não entrega conteúdo
- CloudFront não substitui DNS
- São usados juntos frequentemente

---

## 🔁 Resumo em 1 linha

- **Route 53 = DNS**
- **CloudFront = CDN**

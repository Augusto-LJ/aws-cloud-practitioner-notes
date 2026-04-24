# ⚖️ WAF vs Shield

## 🔗 Referências

- [WAF](../../02-seguranca/waf.md)
- [AWS Shield](../../02-seguranca/aws-shield.md)

---

## 📌 Diferença principal (resumo rápido)

- **WAF** → Proteção na camada de aplicação (L7)
- **Shield** → Proteção contra DDoS (L3/L4)

---

## ⚖️ Comparação direta

| WAF | Shield |
|-----|--------|
| Camada 7 (HTTP/HTTPS) | Camada 3 e 4 |
| Baseado em regras | Automático |
| Bloqueia requisições maliciosas | Mitiga DDoS |
| Protege aplicações web | Protege infraestrutura |

---

## 🎯 Quando usar cada um

### WAF
- Bloquear SQL Injection
- Bloquear IPs específicos
- Filtrar requisições HTTP

---

### Shield
- Proteger contra DDoS
- Garantir disponibilidade
- Defesa contra alto volume de tráfego

---

## 🧠 Pegadinhas de prova

- WAF não protege contra DDoS volumétrico
- Shield não analisa conteúdo HTTP
- Melhor prática: usar os dois juntos

---

## 🔁 Resumo em 1 linha

- **WAF = regras na aplicação**
- **Shield = proteção contra DDoS**

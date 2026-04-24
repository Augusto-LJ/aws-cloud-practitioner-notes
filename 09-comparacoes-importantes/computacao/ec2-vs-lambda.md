# ⚖️ EC2 vs Lambda

## 🔗 Referências

- [EC2](../../01-principais-servicos/computacao/ec2.md)
- [Lambda](../../01-principais-servicos/computacao/lambda.md)

---

## 📌 Diferença principal (resumo rápido)

- **EC2** → Servidores virtuais (você gerencia)
- **Lambda** → Execução de código sem servidor (AWS gerencia)

---

## ⚖️ Comparação direta

| EC2 | Lambda |
|-----|--------|
| Servidor virtual (IaaS) | Serverless |
| Gerenciamento manual | Totalmente gerenciado |
| Sempre ligado | Executa sob demanda |
| Escala manual ou Auto Scaling | Escala automática |
| Paga por tempo ativo | Paga por execução |
| Alto controle | Baixo controle |

---

## 🎯 Quando usar cada um

### EC2
- Aplicações tradicionais (long-running)
- Necessidade de controle do sistema operacional
- Softwares específicos instalados

---

### Lambda
- Aplicações event-driven
- Processamento sob demanda
- APIs simples e microsserviços

---

## 🧠 Pegadinhas de prova

- Lambda tem **limite de tempo de execução**
- Serverless ≠ sem servidor
- EC2 exige gerenciamento (patch, segurança, etc.)
- Auto Scaling no EC2 **não é automático por padrão**

---

## 🔁 Resumo em 1 linha

- **EC2 = controle total**
- **Lambda = simplicidade e escala automática**

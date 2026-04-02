# ⚡ AWS Lambda

## 📌 O que é

O AWS Lambda é um serviço de computação **serverless** que permite executar código sem precisar provisionar ou gerenciar servidores.

Você apenas envia seu código, e a AWS executa automaticamente em resposta a eventos.

---

## 🎯 Quando usar

- APIs (ex: com API Gateway)
- Processamento de eventos (S3, filas, etc.)
- Automações
- Workloads intermitentes ou imprevisíveis

---

## ⚙️ Como funciona

1. Define-se o código da função (o que ela fará)
2. Define-se o que será acionado com base em eventos (trigger)
3. Um evento dispara a execução
4. O Lambda executa a função de acordo com o evento acionado
5. Retorna o resultado

---

## 🔔 Exemplos de gatilhos (triggers)

- Upload no S3
- Requisição HTTP (API Gateway)
- Mensagens em fila (SQS)
- Eventos do sistema (CloudWatch)

---

## 📦 Conceitos importantes

### 🧩 Função Lambda
- Unidade de execução
- Contém o código

---

### ⏱️ Tempo de execução
- Máximo de ~15 minutos por execução

---

### 📈 Escalabilidade automática
- Executa múltiplas instâncias automaticamente conforme demanda

---

### ❄️ Cold Start
- Pequeno atraso na primeira execução após inatividade

---

## 💰 Modelo de cobrança

Você paga por:
- Número de execuções
- Tempo de execução
- Memória alocada

👉 Sem execução = sem custo

---

## 🔒 Segurança

- Controlado via IAM (roles e policies)
- Permissões definem o que a função pode acessar

---

## ⚖️ Lambda vs EC2

| Lambda | EC2 |
|--------|-----|
| Serverless | Infraestrutura gerenciada por você |
| Escala automática | Precisa configurar Auto Scaling |
| Sem gerenciamento de servidor | Controle total do ambiente |
| Cobrança por execução | Cobrança contínua |

---

## 🧠 Conceitos importantes para prova

- Lambda é **serverless**
- Escala automaticamente
- Cobrança por execução
- Executa em resposta a eventos
- Não precisa gerenciar servidor

---

## ⚠️ Pegadinhas comuns

- Não serve para aplicações longas
- Pode ter *cold start*
- Limite de execução (~15 min)
- Menos controle do ambiente

---

## 🔁 Resumo rápido

- Lambda = execução de código sem servidor
- Baseado em eventos
- Escala automaticamente
- Paga apenas pelo uso

---

## 📌 Status de aprendizado

- [ ] Entendo o que é Lambda
- [ ] Sei como funciona execução por eventos
- [ ] Entendo cobrança e limites
- [ ] Sei quando usar Lambda vs EC2

# 🔐 Security Groups

## 📌 O que é

Um Security Group é um firewall virtual que controla tráfego de entrada e saído no **nível da instância (ex: EC2)**.

---

## ⚙️ Características

- Stateful (lembra conexões)
- Mais simples que NACL
- Pode utilizar o mesmo grupo de segurança para diferentes instâncias se quiser

---

## 🔄 Stateful

- Respostas são automaticamente permitidas
- Não precisa regra de saída separada
- Grupos de segurança se lembram de decisões anteriores tomadas para pacotes recebidos
<img width="928" height="311" alt="image" src="https://github.com/user-attachments/assets/cb82d167-2684-467b-934e-4eb881cc37a7" />


---

## 📜 Regras padrão

- Entrada: negado
- Saída: permitido

---

## 🧠 Analogia
- Suponha que você esteja em um prédio com um porteiro que recebe as visitas no lobby.
- Nesse exemplo, as visitas são pacotes e o porteiro é um grupo de segurança.
- À medida que as visitas chegam, o porteiro verifica uma lista para garantir que eles podem entrar no edifício.
  - No entanto, o porteiro não verifica a lista novamente quando as visitas saem do edifício

---

## 🔗 Associação

- Pode ser usado em:
  - EC2
  - RDS
  - outros recursos

---

## 🧠 Conceitos para prova

- Security Group = nível instância
- Stateful
- Mais usado que NACL

---

## 🔁 Resumo

- SG protege recursos individualmente

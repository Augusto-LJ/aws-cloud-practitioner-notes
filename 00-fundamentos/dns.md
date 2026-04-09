# 🌐 DNS (Domain Name System)

O **DNS (Domain Name System)** é o serviço responsável por traduzir nomes de domínio (como `google.com`) em endereços IP (como `142.250.190.78`), permitindo que dispositivos encontrem e se comuniquem com servidores na internet.

Em termos simples, o DNS funciona como uma **agenda telefônica da internet**.

---

## 📌 Como funciona a resolução de DNS

Quando um usuário acessa um site, ocorre o seguinte processo:
<img width="881" height="289" alt="image" src="https://github.com/user-attachments/assets/5c70dcd7-04c2-47fd-b168-7c5ecb315ffd" />

1. O usuário digita um domínio no navegador
2. O dispositivo consulta um **resolvedor DNS**
3. O resolvedor consulta servidores DNS
4. O endereço IP correspondente é retornado
5. O navegador faz a requisição ao servidor usando o IP

---

## 🧠 Analogia

- Domínio → Nome da pessoa  
- IP → Número de telefone  
- DNS → Agenda telefônica  

---

## 🧱 Componentes do DNS

### 🔹 Domínio
Nome amigável usado para acessar recursos  
Ex: `amazon.com`

---

### 🔹 Endereço IP
Identificador único de um servidor na rede

---

### 🔹 Resolvedor DNS
Responsável por iniciar a busca pelo IP de um domínio

---

### 🔹 Servidores DNS
Armazenam os registros que fazem a associação entre domínio e IP

---

## 📑 Tipos de registros DNS

- **A** → Domínio → IPv4  
- **AAAA** → Domínio → IPv6  
- **CNAME** → Alias para outro domínio  
- **MX** → Servidores de e-mail  
- **TXT** → Informações adicionais (ex: verificação)

---

## ☁️ DNS na AWS

Na AWS, o serviço responsável por DNS é o **Amazon Route 53**.

Principais funcionalidades:

- Registro de domínios
- Gerenciamento de registros DNS
- Roteamento de tráfego (latência, geolocalização, failover)
- Health checks

---

## 🔗 Integração com outros serviços

O DNS é fundamental para:

- Load Balancers (ELB)
- CDN (CloudFront)
- Arquiteturas de alta disponibilidade

---

## 🎯 Resumo

- DNS traduz nomes de domínio em IPs  
- É essencial para o funcionamento da internet  
- Permite acesso a aplicações de forma amigável  
- Na AWS, é implementado pelo Amazon Route 53  

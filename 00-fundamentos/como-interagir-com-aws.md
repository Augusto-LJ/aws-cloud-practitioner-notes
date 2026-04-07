# 🧭 Como interagir com os serviços da AWS

## 📌 Visão geral

Existem três principais formas de interagir com os serviços da AWS:

- Console de Gerenciamento (interface gráfica)
- AWS CLI (linha de comando)
- SDKs (via código)

Cada uma atende a diferentes necessidades, desde uso manual até automação avançada.

---

## 🖥️ Console de Gerenciamento da AWS

### 📌 O que é

O Console de Gerenciamento da AWS é uma interface web que permite acessar e gerenciar serviços da AWS.

---

### 🎯 Quando usar

- Uso manual
- Aprendizado
- Configurações rápidas
- Visualização de recursos

---

### ⚙️ Características

- Interface gráfica amigável
- Busca por serviços
- Acesso rápido aos serviços recentes
- Assistentes (wizards) para configuração

---

### 📱 Console Mobile

- Aplicativo mobile da AWS
- Permite:
  - Monitorar recursos
  - Ver alarmes
  - Acompanhar custos

---

### ✅ Vantagens

- Fácil de usar
- Não exige conhecimento técnico avançado
- Ideal para iniciantes

---

### ⚠️ Desvantagens

- Não é ideal para automação
- Pode ser lento para tarefas repetitivas

---

## 💻 AWS CLI (Command Line Interface)

### 📌 O que é

O AWS CLI é uma ferramenta que permite interagir com a AWS via linha de comando.

---

### 🎯 Quando usar

- Automação de tarefas
- Execução de scripts
- Operações repetitivas
- Administração via terminal

---

### ⚙️ Características

- Funciona em:
  - Windows
  - Linux
  - macOS
- Baseado em comandos
- Interage diretamente com APIs da AWS

---

### 🧪 Exemplo de uso
```bash
aws ec2 run-instances ...
```
---

### ✅ Vantagens

- Automação
- Rapidez
- Reprodutibilidade

---

### ⚠️ Desvantagens

- Curva de aprendizado maior
- Menos visual

---

## 🧩 SDKs (Software Development Kits)

### 📌 O que é

Os SDKs são bibliotecas que permitem acessar serviços da AWS diretamente por código.

---

### 🎯 Quando usar

- Desenvolvimento de aplicações
- Integração com AWS
- Criação de sistemas automatizados

---

### ⚙️ Características

- Suporte a várias linguagens:
  - C#
  - Java
  - Python
  - JavaScript
  - C++
- Abstraem chamadas de API
- Integração direta com aplicações

---

### 🧪 Exemplo (pseudo-código)

```bash
ec2.RunInstances(...);
```
---

### ✅ Vantagens

- Total automação
- Integração com sistemas
- Alto nível de controle

---

### ⚠️ Desvantagens

- Requer programação
- Maior complexidade

---

## ⚖️ Comparação geral

| Método | Uso principal | Nível técnico | Automação |
|--------|--------------|--------------|-----------|
| Console | Manual | Baixo | Não |
| CLI | Scripts | Médio | Sim |
| SDK | Código | Alto | Sim |

---

## 🧠 Conceitos importantes para prova

- Console → interface gráfica
- CLI → linha de comando
- SDK → integração via código
- Todos utilizam APIs da AWS por trás

---

## ⚠️ Pegadinhas comuns

- Achar que CLI e SDK são coisas diferentes da API (na verdade usam a API)
- Pensar que Console é a única forma de uso
- Confundir CLI com SDK

---

## 🔁 Resumo rápido

- Console → fácil e visual
- CLI → rápido e automatizável
- SDK → integração via código

---

## 📌 Status de aprendizado

- [ ] Sei quando usar Console
- [ ] Sei quando usar CLI
- [ ] Sei quando usar SDK
- [ ] Entendo que todos usam APIs

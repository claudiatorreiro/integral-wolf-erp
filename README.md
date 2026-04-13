# 🐺 Integral Wolf

ERP Web para gestão administrativa e financeira de pequenas empresas  
(Financeiro · Comercial · Estoque)

---

## 🚀 Sobre o projeto

O **Integral Wolf** é um sistema web desenvolvido em Django com foco na organização e centralização de processos administrativos de pequenas empresas.

A aplicação integra funcionalidades de gestão de clientes, contratos e controle financeiro, substituindo controles manuais e promovendo mais eficiência, rastreabilidade e melhor tomada de decisão.

---

## 🎯 Problema que resolve

Pequenas empresas frequentemente utilizam planilhas, anotações manuais ou sistemas fragmentados para controlar suas operações, o que gera:

- Falta de organização dos dados  
- Dificuldade no acompanhamento financeiro  
- Risco de erros e inconsistências  
- Baixa visibilidade das informações  

O Integral Wolf resolve esse problema centralizando todas essas operações em um único sistema.

---

## 🛠️ Tecnologias utilizadas

### Backend
- Python 3.x
- Django 6.0

### Interface
- Django Templates
- Bootstrap 5
- HTML5
- CSS3

### Formulários
- Django Crispy Forms
- Crispy Bootstrap 5

### Banco de Dados
- SQLite (ambiente de desenvolvimento)
- dj-database-url (configuração por ambiente)

### Servidor e Deploy
- WhiteNoise (arquivos estáticos)
- Gunicorn
- Uvicorn

---

## ⚙️ Funcionalidades principais

- 🔐 Autenticação de usuários  
- 📊 Dashboard com visão geral do sistema  
- 👥 Gestão de clientes (cadastro, edição e listagem)  
- 📄 Gestão de contratos  
- 💰 Controle de recebimentos  
- 📉 Controle de gastos  
- 🔍 Visualização detalhada de contratos  
- 📌 Organização administrativa e financeira integrada  

---

## 📸 Demonstração do sistema

### 🔐 Tela de Login
![Login](assets/1%20-%20Tela%20de%20login%20-%20INTEGRAL%20WOLF.png)

### 📊 Dashboard
![Dashboard](assets/2%20-%20Dashboard%20-%20INTEGRAL%20WOLF.png)

### 👥 Gestão de Clientes
![Clientes](assets/3%20-%20Clientes%20-%20INTEGRAL%20WOLF.png)
![Novo Cliente](assets/4%20-%20Inclusão%20de%20clientes%20-%20INTEGRAL%20WOLF.png)
![Editar Cliente](assets/5%20-%20Edição%20de%20clientes%20-%20INTEGRAL%20WOLF.png)

### 📄 Gestão de Contratos
![Contratos](assets/7%20-%20Lista%20de%20contratos%20-%20INTEGRAL%20WOLF.png)
![Detalhes](assets/6%20-%20Detalhes%20contratos%20-%20INTEGRAL%20WOLF.png)
![Edição](assets/8%20-%20Edição%20contratos%20-%20INTEGRAL%20WOLF.png)

### 💰 Financeiro
![Recebimentos](assets/9%20-%20Recebimentos%20-%20INTEGRAL%20WOLF.png)
![Novo Recebimento](assets/11%20-%20Novos%20recebimentos%20-%20INTEGRAL%20WOLF.png)
![Edição Recebimento](assets/10%20-%20Edição%20recebimentos%20-%20INTEGRAL%20WOLF.png)

### 📉 Controle de Gastos
![Gastos](assets/12%20-%20Gastos%20-%20INTEGRAL%20WOLF.png)
![Novo Gasto](assets/14%20-%20Novos%20gastos%20-%20INTEGRAL%20WOLF.png)
![Edição Gasto](assets/13%20-%20Edição%20gastos%20-%20INTEGRAL%20WOLF.png)

---

## 🧩 Regras e decisões técnicas

- Uso de modelo de usuário customizado (`AUTH_USER_MODEL`)
- Configuração de autenticação com redirecionamentos definidos
- Separação entre ambiente de desenvolvimento e produção
- Gerenciamento de arquivos estáticos com WhiteNoise
- Estrutura preparada para uso de banco em produção via `dj-database-url`
- Internacionalização configurada para português (pt-BR)
- Fuso horário configurado para América/São Paulo

---

## 💡 Diferenciais do projeto

- Estrutura organizada seguindo padrão MVT do Django  
- Integração entre áreas administrativas e financeiras  
- Modelagem baseada em problemas reais de gestão  
- Interface simples e funcional voltada ao uso prático  
- Projeto preparado para evolução e escalabilidade  

---

## 🎯 Contexto de desenvolvimento

Projeto desenvolvido no contexto do programa **Bolsa Futuro Digital**, como parte da formação em desenvolvimento backend com Python e Django.

Este projeto representa a aplicação prática dos conhecimentos adquiridos, com foco na construção de uma solução funcional e alinhada a necessidades reais de negócio.

---

## 🚀 Próximos passos

- Migração para PostgreSQL em ambiente de produção  
- Implementação de autenticação mais robusta  
- Deploy em ambiente cloud  
- Melhorias na experiência do usuário (UI/UX)  
- Expansão do dashboard com indicadores e relatórios  

---

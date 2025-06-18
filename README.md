# blog
# ☁️ Blog na Nuvem com Azure

Este projeto demonstra como criar, configurar e hospedar um blog simples na nuvem utilizando serviços da **Microsoft Azure**, como **App Service** ou **Container Apps**.

---

## 🚀 Objetivo

Aprender na prática como funciona o processo de deploy e hospedagem de aplicações web na nuvem usando a Azure, além de compreender conceitos como escalabilidade e gerenciamento via portal.

---

## 🧰 Tecnologias Utilizadas

- Linguagem: Python (Flask) ou Node.js
- Hospedagem: Azure App Service (PaaS)
- Banco de Dados: SQLite (local) ou Azure SQL
- CI/CD: GitHub Actions (opcional)

---

## 🛠️ Etapas Realizadas

1. Desenvolvimento do blog localmente
2. Criação do recurso App Service no portal Azure
3. Configuração de publicação via GitHub
4. Deploy e testes no ambiente de produção

---

## 🖼️ Prints

| Descrição | Imagem |
|----------|--------|
| App Service configurado | ![](./screenshots/appservice-deploy.png) |
| Blog funcionando online | ![](./screenshots/blog-online.png) |

---

## 🔐 Segurança e Escalabilidade

- Aplicação com HTTPS fornecido pela Azure
- Escalabilidade automática configurável no App Service Plan
- Logs disponíveis no Application Insights

---

## 🧠 Insights

- O Azure App Service facilita muito o deploy de apps web sem precisar gerenciar VMs
- O uso de CI/CD com GitHub Actions permite integração rápida e segura
- O Container Apps é ótimo para workloads mais controlados com Docker

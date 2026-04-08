# KitchenFlow 🍔

Sistema de gestão de cozinha desenvolvido para pequenos restaurantes e hamburguerias que operam com pedidos via WhatsApp.

---

## 🚀 Problema

Muitos negócios pequenos enfrentam dificuldades operacionais no dia a dia:

- pedidos chegando de forma desorganizada (WhatsApp)
- erros na cozinha
- atrasos em horários de pico
- falta de visibilidade do fluxo de produção

Sem um sistema adequado, o processo depende de anotações manuais e comunicação informal.

---

## 💡 Solução

O KitchenFlow transforma esse cenário em um fluxo organizado e visual:

- quadro de pedidos em formato kanban
- separação por status (novo, preparando, pronto, cancelado)
- atualização simples e rápida pela equipe
- visualização clara em tempo real
- notificação apenas quando um novo pedido chega (sem ruído)
- base de dados simples utilizando Google Sheets

---

## ⚙️ Tecnologias

- React
- Node.js (Express)
- Google Sheets
- Google Apps Script

---

## 🧠 Arquitetura

![Arquitetura](docs/architecture.png)

O sistema foi projetado considerando restrições reais de custo e operação.

---

## 📸 Preview

![Kanban](docs/images/kanban.png)  
![Modo Fullscreen](docs/images/fullscreen.png)

---

## 🎥 Demonstração

👉 [Ver demo do sistema](COLE_AQUI_SEU_LINK)

---

## 🧩 Funcionalidades

- organização de pedidos em colunas operacionais
- atualização de status em tempo real (via polling controlado)
- soft delete (remoção visual sem perda de histórico)
- modo fullscreen para uso em cozinha
- alerta apenas para novos pedidos
- destaque visual para pedidos urgentes

---

## 🎯 Abordagem

Este projeto foi desenvolvido com foco em resolver um problema real, respeitando limitações reais do cliente.

A escolha da arquitetura priorizou:

- baixo custo de implementação
- facilidade de adoção
- rapidez de entrega
- possibilidade de evolução futura

---

## 🚀 Evolução futura

- migração para banco de dados (PostgreSQL / Supabase)
- comunicação em tempo real (WebSockets)
- integração com impressora térmica
- suporte a múltiplos restaurantes
- dashboard de métricas

---
## 💼 Observação

O código fonte deste projeto é privado.


Este repositório tem como objetivo apresentar a solução, arquitetura e abordagem utilizada.

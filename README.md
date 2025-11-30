![CI/CD Pipeline](https://github.com/felipebcarlos/10CLDR_TF_DEVOPS_CI-CD/actions/workflows/pipeline.yml/badge.svg)

# Trabalho Final - DevOps (Turma 10CLDR)

Este repositório contém a entrega do trabalho final da disciplina de DevOps CI/CD.

## 📋 Sobre o Projeto
Uma aplicação web estática desenvolvida com **React** e **Vite**, utilizando um pipeline automatizado de CI/CD via **GitHub Actions** para realizar testes de qualidade e deploy automático no **GitHub Pages**.

## 🚀 Tecnologias Utilizadas
* [React](https://react.dev/)
* [Vite](https://vitejs.dev/)
* [GitHub Actions](https://github.com/features/actions) (Automação)
* [GitHub Pages](https://pages.github.com/) (Hospedagem)

## 🔗 Link do Projeto
* **[Acesse a Aplicação Online](https://felipebcarlos.github.io/10CLDR_TF_DEVOPS_CI-CD/)**

## ⚙️ Estrutura do Pipeline (3 Steps)
O fluxo de CI/CD foi configurado para executar automaticamente a cada `push` na branch `main`:

1.  **Checkout & Setup:** Baixa o código fonte e prepara o ambiente Node.js.
2.  **Lint & Quality:** Verifica a integridade do código e padrões de escrita.
3.  **Build & Deploy:** Gera a versão de produção e publica no GitHub Pages.
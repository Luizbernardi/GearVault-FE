# GearVault

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![PrimeNG](https://img.shields.io/badge/PrimeNG-4CAF50?style=for-the-badge&logo=primeng&logoColor=white) ![PrimeFlex](https://img.shields.io/badge/PrimeFlex-2196F3?style=for-the-badge&logo=primeflex&logoColor=white)

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades Principais](#funcionalidades-principais)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Executando o Projeto](#executando-o-projeto)
- [Comandos Úteis](#comandos-úteis)
- [Testes](#testes)

---

## Sobre o Projeto

O **GearVault** é um sistema de gerenciamento de estoque e aquisições de componentes eletrônicos desenvolvido em **Angular**. Ele utiliza **PrimeNG** e **PrimeFlex** para criar uma interface moderna, responsiva e funcional.

Este projeto foi gerado usando **Angular CLI versão 19.0.6**.

### Principais Objetivos

- Facilitar o controle de compras e gerenciamento de estoque.
- Automatizar processos como extração de dados de invoices.
- Rastrear estoque e gerar relatórios detalhados.
- Atender instituições de pesquisa, laboratórios tecnológicos e empresas que lidam com aquisição e armazenamento de componentes.

---

## Funcionalidades Principais

✅ **Upload de Invoices**: Permite o upload de invoices (documentos de compra) e extração automática de dados.

✅ **Controle de Estoque**: Exibe a quantidade disponível de cada componente e sua localização de armazenamento.

✅ **Histórico de Compras**: Visualize todas as compras realizadas no passado, com filtros avançados.

✅ **Relatórios Personalizados**: Gere relatórios detalhados sobre compras e estoque.

✅ **Interface Responsiva**: Design adaptável para diferentes dispositivos (desktops, tablets e smartphones).

---

## Pré-requisitos

Antes de iniciar o projeto, certifique-se de que você tenha as seguintes ferramentas instaladas:

- **[Node.js](https://nodejs.org/)** (Versão 16 ou superior)
- **[Angular CLI](https://angular.io/cli)** (Versão 19 ou superior)
  ```bash
  npm install -g @angular/cli
  ```
- **[Git](https://git-scm.com/)** (Para clonar o repositório)

---

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/gearvault.git
   cd gearvault
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Verifique as variáveis de ambiente:
   Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis (se aplicável):
   ```env
   API_URL=http://localhost:3000/api
   JWT_SECRET=your-secret-key
   ```

---

## Executando o Projeto

1. Inicie o servidor de desenvolvimento:
   ```bash
   ng serve
   ```
2. Acesse o projeto no navegador:
   ```
   http://localhost:4200
   ```


---

## Comandos Úteis

🔹 **Gerar um novo componente:**
   ```bash
   ng generate component nome-do-componente
   ```
🔹 **Compilar o projeto:**
   ```bash
   ng build
   ```
🔹 **Executar testes unitários:**
   ```bash
   ng test
   ```
🔹 **Executar testes de ponta a ponta (E2E):**
   ```bash
   ng e2e
   ```

---

## Testes

### Testes Unitários
Para executar testes unitários com **Karma**, utilize:
```bash
ng test
```

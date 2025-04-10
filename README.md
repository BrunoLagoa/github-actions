# 🚀 GitHub Actions Pipeline Demo

> Um projeto demonstrativo de CI/CD usando GitHub Actions

## 📋 Sobre o Projeto

Este projeto é uma demonstração prática de como implementar um pipeline de CI/CD (Integração Contínua/Entrega Contínua) usando GitHub Actions. O pipeline automatiza o processo de teste, build e deploy de uma aplicação Node.js.

## 🔧 Configuração do Pipeline

O pipeline é configurado para executar automaticamente quando há um push em qualquer branch do repositório e inclui as seguintes etapas:

1. **Checkout do Código**
2. **Setup do Node.js (v18.x)**
3. **Instalação de Dependências**
4. **Execução de Testes**
5. **Build do Projeto**
6. **Deploy da Aplicação**

## 🛠️ Tecnologias Utilizadas

- Node.js
- GitHub Actions
- npm

## 🚀 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/BrunoLagoa/github-actions.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute os testes:
   ```bash
   npm test
   ```

4. Faça o build:
   ```bash
   npm run build
   ```

5. Execute o deploy:
   ```bash
   npm run deploy
   ```

## 📦 Scripts Disponíveis

- `npm test` - Executa os testes do projeto
- `npm run build` - Gera o build do projeto
- `npm run deploy` - Realiza o deploy da aplicação

## 👨‍💻 Autor

Bruno Castro

## 📄 Licença

Este projeto está sob a licença ISC.

---

⭐ Se este projeto te ajudou, não esqueça de deixar uma estrela!
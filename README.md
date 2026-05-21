# Polvilhos Pingo de Ouro 🌾

Uma landing page estática, moderna e responsiva desenvolvida para a **Polvilhos Pingo de Ouro**. O site tem como foco a captação de clientes B2B (indústrias, fábricas e food service), apresentando a qualidade da lavoura, os diferenciais logísticos e o catálogo de produtos (Polvilho Azedo, Polvilho Doce e Mandioca Amarela).

## 🚀 Funcionalidades

- **Design Responsivo:** Adaptado para funcionar perfeitamente em dispositivos móveis, tablets e desktops (Mobile-first).
- **Alta Performance:** Construído exclusivamente com HTML, CSS e Vanilla JS, garantindo carregamento rápido, sem dependências de bibliotecas pesadas.
- **Captação de Leads Integrada:** Modal de contato customizado que coleta a demanda do cliente (produtos, quantidade mensal e cidade) e constrói uma mensagem automatizada, redirecionando para o WhatsApp ou E-mail da equipe comercial.
- **Deploy Automatizado:** Configurado com GitHub Actions para publicar as atualizações diretamente no GitHub Pages.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e acessível.
- **CSS3:** Estilização utilizando variáveis (Custom Properties), CSS Grid, Flexbox e propriedades modernas como `clamp()` para tipografia fluida.
- **JavaScript (Vanilla):** Lógica de abertura/fechamento do modal, interações de formulário e montagem de links dinâmicos para WhatsApp/E-mail.
- **Tipografia:** Fontes do Google (DM Sans e Fraunces).

## 📦 Como executar localmente

Por ser um projeto puramente estático (sem backend ou processos de build complexos), rodar o projeto localmente é muito simples:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/polvilhopingodeouro.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd polvilhopingodeouro
   ```

3. Abra o arquivo `index.html` diretamente no seu navegador, ou utilize extensões como o **Live Server** (no VS Code) para visualizar o site com auto-reload ao salvar os arquivos.

## 🌐 Deploy (GitHub Pages)

O repositório já conta com um workflow (`.github/workflows/static.yml`) configurado. Toda vez que um novo código for integrado à branch `main`, o GitHub Actions fará o deploy automático e as alterações entrarão no ar instantaneamente via **GitHub Pages**.

---

*© Polvilhos Pingo de Ouro · Da nossa lavoura em Minas Gerais ao seu chão de fábrica.*
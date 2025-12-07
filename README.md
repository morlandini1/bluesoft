# 🚀 BlueSoft Solutions - Landing Page

Este projeto consiste no desenvolvimento de uma *Landing Page* institucional para a empresa fictícia **BlueSoft Solutions**, especializada em transformação digital para pequenos negócios.

O trabalho foi desenvolvido como parte da disciplina de **Padrões Web para No Code e Low Code**, com o objetivo de demonstrar domínio em HTML Semântico, CSS Customizado e Integrações via API (JavaScript + Make).

---

## 📋 Funcionalidades

* **Design Responsivo:** Layout adaptável para Desktops, Tablets e Smartphones.
* **Menu Mobile (Gaveta):** Navegação lateral animada para dispositivos móveis.
* **Design System:** Uso de Variáveis CSS (`:root`) para consistência de cores (Tons de Azul) e espaçamentos.
* **Componentização:** Botões e Cards padronizados via classes CSS.
* **Integração Real:** Formulário de contato conectado ao **Make (Integromat)** via Webhook.
    * Salva os dados no **Google Sheets**.
    * Envia e-mail de confirmação automática.
* **Seções Informativas:** Hero, Serviços, Depoimentos, Estatísticas e Redes Sociais.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica (`<header>`, `<main>`, `<section>`, `<footer>`).
* **CSS3:** Flexbox, Grid Layout, Media Queries e Variáveis CSS.
* **JavaScript (Vanilla):** Manipulação do DOM, eventos de clique e Fetch API para envio de dados.
* **Make (antigo Integromat):** Automação de backend (Webhook -> Sheets -> Gmail).
* **Font Awesome:** Biblioteca de ícones.
* **Google Fonts:** Tipografia (Fonte *Inter*).

---

## 📂 Estrutura do Projeto

```text
/
├── index.html          # Estrutura principal da página
├── style.css           # Estilos globais e responsividade
├── script.js           # Lógica do menu e integração do formulário
├── README.md           # Documentação do projeto
└── assets/
    └── icone.png       # Favicon e Logo da empresa

    ⚙️ Como Configurar e Rodar
1. Clonar ou Baixar
Baixe os arquivos do projeto para uma pasta em seu computador.

2. Configurar a Integração (Importante)
Para que o formulário de contato funcione, é necessário configurar o Webhook no arquivo JavaScript.

Abra o arquivo script.js.

Localize a linha: const WEBHOOK_URL = 'https://hook.us2.make.com/mudnbspui5ol2x6ueyw1jjpe2sguujmw';

Substitua o valor pelo seu link de Webhook gerado no Make.com.

3. Executar o Projeto
Basta abrir o arquivo index.html em qualquer navegador moderno (Chrome, Edge, Firefox).

Dica: Para visualizar o Favicon corretamente, recomenda-se abrir o projeto através de um servidor local (como a extensão "Live Server" do VS Code) ou hospedar em serviços como GitHub Pages ou Vercel.

🧩 Detalhes da Integração (Make.com)
O fluxo de dados segue o seguinte caminho:

Gatilho (Trigger): O JavaScript intercepta o submit do formulário e envia um JSON via POST para o Webhook do Make.

Ação 1 (Google Sheets): O Make recebe os dados (nome, email, empresa, mensagem) e adiciona uma nova linha na planilha "Leads BlueSoft".

Ação 2 (Gmail/Email): O Make dispara um e-mail de agradecimento para o endereço fornecido pelo usuário.

🎨 Decisões de Design (Justificativa)
Minimalismo: O uso excessivo de elementos foi evitado para focar na conversão (Botão "Solicitar Orçamento").

Paleta de Cores:

--primary-blue (#0044cc): Transmite confiança e tecnologia.

--secondary-blue (#f0f4ff): Usado para quebrar a monotonia do fundo branco e separar seções visualmente.

Tipografia: A fonte Inter foi escolhida por sua excelente legibilidade em telas digitais.

Autor
Desenvolvido por Marcio Orlandini para a entrega da atividade acadêmica da UniFECAF.


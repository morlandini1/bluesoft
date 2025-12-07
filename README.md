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

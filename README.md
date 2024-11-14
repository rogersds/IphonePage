# 📱  iPhone 13 Pro - Interface Interativa de Cores
Este projeto é uma interface de demonstração para a página de apresentação do iPhone 13 Pro. A interface permite ao usuário selecionar diferentes opções de cores para visualizar o dispositivo em várias variações, simulando a experiência de escolher e personalizar um produto no site oficial da Apple.

### 📋 Tabela de Conteúdos
### 📖 Sobre o Projeto
### 📁 Estrutura de Arquivos
### ✨Funcionalidades
### 🛠Tecnologias Utilizadas
#### 👤 Autor

## 📖Sobre o Projeto
Esta interface foi desenvolvida como parte de um projeto de estudo de HTML, CSS e JavaScript, com foco na criação de componentes dinâmicos e na aplicação de transições visuais. O objetivo é replicar a interatividade típica de uma página de produtos, permitindo ao usuário experimentar diferentes estilos e opções do iPhone.

### 📁Estrutura de Arquivos

#### plaintext
Copiar código
iphone-13-pro
│
├── index.html              # Estrutura básica HTML da página 

├── css
│   └── styles.css          # Estilos da página e transições de cores

└── js
    └── scripts.js          # Script principal para a lógica de mudança de cor
└── img                     # Imagens do iPhone 13 Pro em diferentes cores
    ├── iphone_green.jpg
    ├── iphone_silver.jpg
    ├── iphone_golden.jpg
    ├── iphone_grafite.jpg
    └── iphone_blue.jpg

## 💻 Lógica do JavaScript
O arquivo scripts.js é responsável por adicionar a interatividade à interface. Abaixo está o código JavaScript e uma explicação detalhada do que cada parte faz:


### Explicação da Lógica

Seleção de Elementos:
O código seleciona todos os botões de cor (#image-picker li) e a imagem principal do produto (#product-image).

Adicionar Event Listeners:
Para cada botão de cor, um listener de evento click é adicionado, ativando a função de mudança de cor.

Remover Seleção Atual:
Antes de aplicar uma nova seleção, a classe selected é removida de todos os botões de cor para garantir que apenas um esteja destacado.

Identificação da Cor Selecionada:
Quando um botão é clicado, seu id é capturado para que a imagem correspondente possa ser carregada.

Aplicar Transição de Imagem:
A imagem é temporariamente opacificada aplicando a classe changing, criando uma transição suave de cor.
O atributo src da imagem é alterado para a nova imagem com base no id da cor selecionada.
Após 200 milissegundos, a classe changing é removida, restaurando a opacidade original.

## ✨Funcionalidades
🎨 Mudar de cor: Ao clicar nos círculos de cor abaixo da imagem, a imagem do iPhone muda para o modelo correspondente.
🔄 Transição suave: Ao selecionar uma nova cor, a imagem do produto é suavemente opacificada para uma transição visual agradável.
✅ Indicação visual de seleção: A cor selecionada atualmente é destacada com uma borda.
🛠 Tecnologias Utilizadas
🌐 HTML5: Para a estrutura da página.
🎨 CSS3: Para o estilo e a animação de transição.
💻 JavaScript: Para a interatividade de seleção de cores.

# 🛒 Zaffari Express Route

Um Web App PWA simples, leve e responsivo projetado para otimizar o trajeto de compras dentro dos supermercados e hipermercados **Zaffari / Bourbon**.

O aplicativo organiza a lista de compras gerando um circuito perimétrico otimizado (*U-Loop / S-Shape*) com base na localização física dos setores da loja, evitando que você precise cruzar os corredores ida e volta.

---

## 🚀 Funcionalidades

- **Circuito Otimizado:** Mapeamento de 18 setores com base na planta clássica das lojas Zaffari (Entrada e Saída pela **Entrada 1**).
- **Persistência Local (LocalStorage):** Os itens inseridos permanecem salvos no navegador mesmo se você fechar o app.
- **Sincronização em Tempo Real (Opcional):** Integração com **Firebase Realtime Database** para que mais de uma pessoa (ex: casal) adicione itens na mesma lista durante a semana.
- **Suporte PWA (iOS / Safari):** Ícone personalizado e suporte para instalação direta na tela de início do iPhone ("Add to Home Screen").
- **Modo Escuro / Claro:** Alternância rápida de tema com salvamento automático.
- **Entrada Rápida:** Adição de produtos pressionando a tecla `Enter` ou botão físico do teclado.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & JavaScript (ES6+):** Sem frameworks pesados ou etapas de build.
- **Tailwind CSS (via CDN):** Interface moderna e responsiva.
- **Firebase Realtime Database (via CDN):** Sincronização multi-dispositivo.

---

## 📱 Como instalar no iPhone (iOS)

1. Acesse o link do app hospedado (GitHub Pages) pelo **Safari**.
2. Toque no botão de **Compartilhar** (ícone do quadrado com a seta para cima na barra inferior).
3. Role para baixo e selecione **"Adicionar à Tela de Início"**.
4. O app será instalado na tela do iPhone com ícone próprio e abrirá em tela cheia (sem as barras do navegador).

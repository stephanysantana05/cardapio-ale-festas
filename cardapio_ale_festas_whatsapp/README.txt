# Cardápio Alê Festas (HTML)

Este pacote contém um **cardápio responsivo** (rosa e branco) com:
- Lista de salgados (Tabela I) e **preço R$120,00 o cento**
- Imagens ilustrativas (placeholders SVG)
- Botão de **WhatsApp**
- **QR Code** que aponta para o link do cardápio (atualize a variável `cardapio_url` no HTML)

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `cardapio-ale-festas`).
2. Envie estes arquivos para o repositório.
3. Vá em **Settings → Pages → Deploy from a branch → main / root**.
4. O GitHub vai gerar um link, ex.: `https://seu-usuario.github.io/cardapio-ale-festas`.

## Como atualizar o QR Code
1. Abra `index.html`.
2. Procure por `cardapio_url` no arquivo.
3. Substitua pelo link real do seu cardápio publicado.
4. Salve e publique.

## Como trocar o WhatsApp
- No final do `index.html`, altere `WHATSAPP_NUMBER` para o seu número no formato internacional. Ex.: `55119XXXXXXXX`.

## Trocar logo e fotos
- Substitua `assets/logo.jpg` pela sua logo real (mesmo nome).
- As imagens dos produtos estão em `assets/*.svg`. Você pode substituir por fotos reais (ex.: `.jpg` com o mesmo nome do arquivo).

Feito com ❤️

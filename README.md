# Simulador de Prova Atletis

Página única (HTML, CSS e JS num só arquivo) que mostra onde o atleta está agora, a que horas passa em cada ponto do percurso e onde ficar para torcer. Sem backend e sem captura de dados. O estado fica só no navegador de quem usa (localStorage).

Versão publicada: 1.05 (MVP).

Endereço: https://atletis-ltda.github.io/simulador-de-prova/

## Arquivos

- `index.html`: a página inteira.
- `og.png`: imagem de preview (1200x630) para WhatsApp, Instagram e redes.
- `favicon.ico`, `favicon-32.png`, `apple-touch-icon.png`: ícone do A da Atletis (aba do navegador e tela inicial do celular).
- `.nojekyll`: faz o GitHub Pages servir os arquivos como estão.

## Publicar

GitHub Pages: Settings, Pages, Deploy from a branch, branch `main`, pasta `/ (root)`.

## Se mudar de endereço

Trocar o novo endereço em 4 lugares do `index.html`: `LINK_SIMULADOR` (script), `og:url`, `canonical` e `og:image` (head), além de `twitter:image`.

Os horários são estimativas feitas pelos ritmos informados e podem variar. A página é independente e não tem vínculo com a organização das provas.

© Atletis. Todos os direitos reservados.

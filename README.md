# Simulador de Prova Atletis

Página única (HTML, CSS e JS num só arquivo) que mostra onde o atleta está agora, a que horas passa em cada ponto do percurso e onde ficar para torcer. Sem backend e sem captura de dados. O estado fica só no navegador de quem usa (localStorage).

Endereço antigo (redireciona): https://atletis-ltda.github.io/simulador-de-prova/

## Endereço

O simulador vive no app da Atletis: https://apps.atletis.com.br/tracker (versão 4.74). O código fica em `mvps/materiais-ricos-2026-10-22/src/simulador.html` do repositório `Atletis-LTDA/atletis-prototipos`, e a publicação é feita pela Vercel.

Este repositório só guarda o redirect: `index.html` leva o acesso antigo para o app, mantendo o `#atleta` e a busca. Não gere este `index.html` de novo a partir da base de conhecimento: isso desfaz o redirect.

- `index.html`: o redirect.
- `og.png`: imagem de preview antiga, sem uso nas páginas novas.
- `favicon.ico`, `favicon-32.png`, `apple-touch-icon.png`: ícones antigos.
- `.nojekyll`: faz o GitHub Pages servir os arquivos como estão.

## Se mudar de endereço

Trocar o redirect deste `index.html` e o `LINK_SIMULADOR` do `src/simulador.html` no repositório `atletis-prototipos`.

Os horários são estimativas feitas pelos ritmos informados e podem variar. A página é independente e não tem vínculo com a organização das provas.

© Atletis. Todos os direitos reservados.

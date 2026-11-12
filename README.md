# Nosso universo 💜

Site completo em roxo e rosa, com as cinco fotos já incluídas e configuradas.
Não precisa instalar programas, usar terminal, configurar API ou alterar código para publicar.

## Publicar no GitHub Pages

1. Extraia este ZIP no computador.
2. Crie um repositório público no GitHub, por exemplo `nosso-universo`.
3. Abra **Add file → Upload files** (ou **uploading an existing file** em um repositório vazio).
4. Arraste TODOS os arquivos extraídos para o repositório. Envie os arquivos, não o ZIP e nem uma pasta que contenha tudo. O `index.html` precisa aparecer diretamente na raiz.
5. Clique em **Commit changes** e salve na branch `main`.
6. Vá em **Settings → Pages**.
7. Em **Source**, selecione **Deploy from a branch**.
8. Em **Branch**, escolha `main`; na pasta, escolha `/(root)`; clique em **Save**.
9. Aguarde a publicação e abra o endereço mostrado nessa mesma página.

Se você já enviou a versão anterior, substitua `index.html`, `style.css`, `app.js` e `README.md` e envie também as cinco fotos. O arquivo antigo `puzzle.svg` não é mais usado.

Referência oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Testar antes de publicar

Abra `index.html` com dois cliques. As fotos e os jogos funcionam localmente. Fontes decorativas usam Google Fonts; sem internet, o navegador usa fontes alternativas.

## O que está incluído

- Capa com fotos em molduras.
- Álbum com as cinco fotos e ampliação sem corte.
- Jogo da memória, corações escondidos e frase para montar.
- Quebra-cabeça de nove peças, com escolha entre as cinco fotos, referência e botão de embaralhar. Fotos verticais mantêm suas proporções.
- Envelopes com mensagens, cartões de carinho, sorteio de encontros, lista de planos e carta.
- Progresso dos desafios e lista de planos salvos no navegador de cada visitante.

## Onde editar depois

| Arquivo | O que controla |
| --- | --- |
| index.html | Textos da página, álbum e capa |
| style.css | Cores, fontes, tamanhos e layout |
| app.js | Jogos, carta, mensagens e opções de encontros |
| foto-por-do-sol.jpg | Foto com o pôr do sol |
| foto-espelho.png | Foto de blusa preta no espelho |
| foto-gamer.jpg | Foto no computador |
| foto-carinho.jpg | Foto com cabelo colorido no espelho |
| foto-divertida.webp | Foto em preto e branco |

Para substituir uma foto, mantenha o nome e o formato do arquivo. Se mudar as proporções de uma imagem, ajuste também o campo `ratio` em `puzzlePhotos` no `app.js` (largura dividida pela altura).

Todos os caminhos são relativos e funcionam em repositórios com qualquer nome. Não há dependência da hospedagem do ChatGPT. As alterações no GitHub Pages não atualizam o link antigo do ChatGPT.

O progresso é individual por navegador, não há contas nem sincronização entre dispositivos. O repositório e a ativação do Pages precisam ser feitos na sua conta; este pacote já contém o site pronto.

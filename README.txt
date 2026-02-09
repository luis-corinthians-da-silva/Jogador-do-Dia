Jogador do Dia — versão para publicar (sem instalação para o visitante)

Arquivos:
- index.html
- players.json  (dados dos jogadores; você pode trocar esse arquivo e o site já lê automaticamente)
- (opcional) jogador-do-dia.players.seed.json/csv: referência

Como funciona:
- Quando o site está hospedado, o index.html tenta carregar players.json.
- Se você abrir o arquivo localmente (duplo clique), pode bloquear fetch por segurança do browser.
  Nesse caso, o site usa o seed embutido no próprio HTML.

Publicar (jeito mais simples):
- Netlify: faça upload da pasta inteira (index.html + players.json)
- GitHub Pages: coloque os arquivos na raiz do repositório e ative Pages


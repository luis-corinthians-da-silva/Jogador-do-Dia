# Jogador do Dia

Dashboard web com **campo interativo** para montar uma escalação com 11 jogadores, arrastar cards, substituir pelo elenco e compartilhar/baixar a escalação.

## Rodar local

> O projeto carrega `players.json` via `fetch()`. Para funcionar localmente, rode um servidor (não abra o HTML no duplo-clique).

```bash
python -m http.server 5173
```

Abra `http://localhost:5173`.

## Build

Não há etapa de build (projeto estático: `index.html` + `players.json` + assets).

## Features principais

- Campo interativo com 11 jogadores arrastáveis (drag-and-drop)
- Cards estilo FUT (overall + bandeira + posição + foto + nome)
- Substituição por clique (Elenco ↔ Campo)
- Swap no campo: clique em um jogador e depois em outro para trocar posições
- Busca no elenco + vazio: “Nenhum jogador encontrado”
- Formações + modo **Livre** (posição do card atualiza pela zona do campo)
- Painel da direita com estados exclusivos (projeto vs jogador selecionado)
- Compartilhar + **Baixar escalação**
- Rating do time atualiza quando o lineup muda (estrutura pronta para fórmula FUT)

## Campo (background)

Por decisão de escopo, o background oficial é:

- `assets/field2.jpg`

Outras variações foram removidas/ignoradas.

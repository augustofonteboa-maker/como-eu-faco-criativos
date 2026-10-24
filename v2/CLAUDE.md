# v2 · Como Criar Criativos (entrega de 23/10/2026)

Página de vendas com VSL do curso Como Criar Criativos, montada com a skill /pagina-foda (kit em augustofonteboa-maker/kit-pagina-foda).

## Onde mora cada coisa
- `index.html`: página inteira (CSS e JS dentro). Imagens em `../img/` (aula, autor, wall).
- Bloco `CFG` no começo do `<script>`: checkout, parcela, à vista, e-mail de suporte, CNPJ, termos, privacidade, minuto da oferta.
- `HEADS`: as três variantes de topo (?h=a principal, ?h=c, ?h=f).
- `?modo=trafego` esconde a página abaixo do vídeo até o minuto da oferta (precisa de `CFG.minutoOferta` > 0 e do player chamando `liberarOferta()`).

## Nunca trocar sem pedir
- Primeira tela: só headline + vídeo + subheadline (sem barra, logo ou botão).
- Chamada do vídeo sempre diz o que a pessoa ganha.
- Fonte Figtree (fácil de ler). Sem cursiva, sem barra de progresso, sem textura listrada.
- Copy literal v1.3.

## Decisões tomadas
- 23/10/2026: episódios num player com playlist (não uma seção por aula).
- 23/10/2026: "Tudo o que você recebe" separado da faixa de preço, para a faixa ficar estreita e o card vazar.
- 23/10/2026: botão fixo no celular depois do topo, some na oferta e no fechamento.
- `noindex` (página de comparação).

## Faltando
- Link do checkout, e-mail de suporte, CNPJ, links de Termos e Privacidade, vídeo da VSL e minuto da oferta.

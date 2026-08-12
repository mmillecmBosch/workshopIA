# 1. Meeting Title

Workshop AI: Levantamento de Requisitos â€” Aplicativo de Assinatura para Criadores de ConteÃºdo

---

# 2. Date & Time

08/12/2026

---

# 3. Participants

- Isabel Sprogis (BD/SWD-TMA2)
- Camille [Sobrenome nÃ£o mencionado]

---

# 4. Executive Summary

A equipe discutiu os requisitos para o desenvolvimento de um aplicativo onde pessoas comuns podem se conectar com criadores de conteÃºdo artÃ­stico e artesanal (crochÃª, pintura, argila, mÃºsica, etc.) atravÃ©s de assinaturas mensais. Foram definidos os principais recursos do MVP, incluindo o modelo de assinatura, o formato de conteÃºdo em estilo blog, o sistema de tags (macro e micro), o feed personalizado e o sistema de avaliaÃ§Ã£o. Itens como free trial de 14 dias e compra de posts individuais foram discutidos, mas deixados fora do escopo do MVP.

---

# 5. Key Discussion Points

## Objetivo do Aplicativo

- Isabel iniciou a discussÃ£o solicitando o desenvolvimento de um aplicativo onde pessoas possam seguir e comprar conteÃºdos de criadores de conteÃºdo, focado principalmente em artes e crafts (crochÃª, trabalhos manuais, etc.).
- O objetivo principal Ã© conectar pessoas que querem aprender com criadores de conteÃºdo artÃ­stico.
- Cada criador de conteÃºdo controla sua prÃ³pria pÃ¡gina e decide o que postar â€” conteÃºdo gratuito ou pago.

## Modelo de MonetizaÃ§Ã£o

- Isabel propÃ´s um modelo de assinatura mensal onde o assinante paga diretamente ao criador de conteÃºdo.
- A plataforma retÃ©m uma porcentagem baixa (aproximadamente 10%) da mensalidade, e os 90% restantes vÃ£o direto para o criador de conteÃºdo.
- Camille questionou se haveria opÃ§Ã£o de compra avulsa de conteÃºdos ou apenas assinatura. Isabel esclareceu que, para o MVP, o modelo serÃ¡ apenas assinatura, liberando acesso a toda a loja do criador.

## Formato do ConteÃºdo

- Camille perguntou sobre o formato de disponibilizaÃ§Ã£o do conteÃºdo (vÃ­deos, fotos, downloads).
- Isabel esclareceu que a plataforma deve suportar vÃ­deos (WMV), imagens (JPEG), PDFs, arquivos de Ã¡udio (MP3), tablaturas (arquivos .tab) e links diretos para o YouTube (para vÃ­deos privados).
- Cada criador gerencia seu prÃ³prio conteÃºdo e pode escolher o formato que desejar.

## Estrutura do ConteÃºdo â€” Estilo Blog

- Camille questionou se o conteÃºdo seria organizado em aulas ou como um repositÃ³rio Ãºnico (estilo "drive").
- Isabel definiu que serÃ¡ no estilo blog, com posts. Cada post terÃ¡ um tÃ­tulo e o conteÃºdo (ex: diagrama de crochÃª, PDF de instruÃ§Ãµes, vÃ­deo demonstrativo).
- O assinante de um criador tem acesso a todos os posts jÃ¡ publicados por ele.
- O criador pode editar e excluir seus prÃ³prios posts a qualquer momento.

## InteraÃ§Ã£o e AvaliaÃ§Ã£o

- Isabel propÃ´s uma Ã¡rea de comentÃ¡rios abaixo de cada post.
- Sistema de curtidas bÃ¡sico (Ã­cone de coraÃ§Ã£o).
- Sistema de avaliaÃ§Ã£o de 1 a 5 estrelas para os criadores de conteÃºdo, disponÃ­vel apenas para usuÃ¡rios que jÃ¡ assinaram o criador pelo menos uma vez.
- O criador pode ler os feedbacks e usar as informaÃ§Ãµes para melhorar seus conteÃºdos.

## Descoberta de Criadores â€” Feed e Busca

- Isabel solicitou uma pÃ¡gina inicial com um feed personalizado.
- No primeiro acesso, o aplicativo pergunta ao usuÃ¡rio quais sÃ£o seus 5 principais interesses (categorias/tags).
- Isabel enviarÃ¡ por e-mail uma lista de categorias possÃ­veis. O objetivo inicial Ã© criar pelo menos 10 categorias.
- O usuÃ¡rio seleciona 5 categorias para personalizar o feed.
- Caixa de busca para encontrar criadores de conteÃºdo pelo nome.
- Criadores terÃ£o nome e nickname para identificaÃ§Ã£o.

## Sistema de Tags

- Isabel propÃ´s dois nÃ­veis de tags: macro tags (ex: crochÃª, pintura, artesanato, argila, mÃºsica) e micro tags (ex: amigurumi, crochet core, etc.).
- Cada criador pode ter atÃ© 5 tags.
- Macro tags sÃ£o usadas na seleÃ§Ã£o inicial do usuÃ¡rio; micro tags sÃ£o usadas na pesquisa e nas sugestÃµes.
- Isabel mencionou a possibilidade de criar um algoritmo de recomendaÃ§Ã£o que relacione interesses (ex: quem gosta de crochÃª pode gostar de tricÃ´, mas nÃ£o necessariamente de resina).

## ConteÃºdo Gratuito vs. Pago

- ConteÃºdo gratuito aparece normalmente no feed.
- ConteÃºdo pago aparece "blurred" (borrado) â€” o tÃ­tulo Ã© visÃ­vel, mas o conteÃºdo estÃ¡ borrado, dando ao usuÃ¡rio uma noÃ§Ã£o do que estÃ¡ disponÃ­vel.
- Ao assinar, o usuÃ¡rio tem acesso total ao conteÃºdo.
- Isabel mencionou a possibilidade de um free trial de 14 dias, mas decidiu deixar isso fora do MVP.

---

# 6. Decisions Made

- O MVP serÃ¡ um aplicativo/site onde pessoas se conectam com criadores de conteÃºdo artÃ­stico e artesanal atravÃ©s de assinaturas mensais.
- O modelo de monetizaÃ§Ã£o do MVP serÃ¡ exclusivamente assinatura mensal (sem compra avulsa de posts individuais).
- A assinatura libera acesso a todo o conteÃºdo publicado pelo criador (estilo blog com posts).
- A plataforma reterÃ¡ aproximadamente 10% da assinatura; 90% vai para o criador.
- O conteÃºdo serÃ¡ organizado em formato de blog (posts com tÃ­tulo e conteÃºdo multimÃ­dia).
- Formatos suportados: vÃ­deos (WMV), imagens (JPEG), PDFs, Ã¡udio (MP3), tablaturas (.tab) e links do YouTube.
- Cada criador pode ter atÃ© 5 tags (macro e micro tags combinadas).
- O feed da pÃ¡gina inicial serÃ¡ personalizado com base em 5 categorias selecionadas pelo usuÃ¡rio no primeiro acesso.
- ConteÃºdo pago aparecerÃ¡ "blurred" (borrado) no feed para nÃ£o-assinantes; apenas o tÃ­tulo serÃ¡ visÃ­vel.
- Sistema de avaliaÃ§Ã£o de 1 a 5 estrelas, disponÃ­vel apenas para usuÃ¡rios que jÃ¡ assinaram o criador.
- Ãrea de comentÃ¡rios e curtidas (coraÃ§Ã£o) em cada post.
- Criadores gerenciam seus prÃ³prios posts (criar, editar, excluir).
- Free trial de 14 dias foi discutido, mas excluÃ­do do MVP.

---

# 7. Action Items

| Owner | Task | Due Date |
|---|---|---|
| Isabel Sprogis | Enviar por e-mail a lista de categorias possÃ­veis para as tags (mÃ­nimo 10 categorias) | TBD |
| Isabel Sprogis | Confirmar lista de macro tags e micro tags para o sistema de tags | TBD |
| Camille | Iniciar documentaÃ§Ã£o de requisitos do MVP com base nesta reuniÃ£o | TBD |
| Camille | Definir algoritmo de recomendaÃ§Ã£o baseado em tags (macro e micro) | TBD |

---

# 8. Follow-ups / Open Questions

- Lista completa de categorias e tags â€” aguardando envio por e-mail da Isabel.
- Algoritmo de recomendaÃ§Ã£o (como linkar interesses relacionados, ex: crochÃª â†’ tricÃ´) â€” a ser discutido em reuniÃ£o futura.
- Modelo de free trial (14 dias) â€” deixado fora do MVP, mas pode ser revisitado em versÃµes futuras.
- Compra avulsa de posts individuais â€” excluÃ­da do MVP, mas pode ser reconsiderada posteriormente.
- Valor exato da assinatura mensal â€” nÃ£o foi definido (mencionado valor aproximado de 10 BRL como exemplo).

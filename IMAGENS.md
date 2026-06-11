# Imagens do hotsite — prompts de IA

Gere cada imagem com a IA de sua preferência (Midjourney, DALL-E, Ideogram, Flux etc.) e salve em `assets/img/` com o nome exato indicado. Depois, no `index.html`, troque a `<div class="img-slot" data-img="NOME.png">` pelo `<img>` indicado no comentário HTML ao lado de cada slot (mantendo `width`/`height` para evitar layout shift).

**Diretrizes comuns a todas:** pessoas brasileiras/diversas, ambientes de salão modernos e iluminados, acento azul-cobalto (#3B82F6) quando couber, **sem texto legível** gerado pela IA (telas de app devem ser abstratas/borradas — IA erra texto).

---

## 1. ✅ `hero-app-mockup.jpg` — Hero (já gerada e aplicada)

> 3D render of a floating smartphone and laptop displaying a modern salon management app interface, calendar view with colorful appointment blocks, clean white UI with cobalt blue (#3B82F6) accents, dark navy blue background with soft blue glow, abstract blurred UI labels with no readable text, premium tech product mockup style, high detail, studio lighting

*Tradução: render 3D de um smartphone e um notebook flutuando exibindo a interface de um app moderno de gestão de salão, visão de calendário com blocos coloridos de agendamento, UI branca limpa com acentos azul-cobalto, fundo azul-marinho escuro com brilho azul suave, rótulos de UI abstratos e borrados sem texto legível, estilo mockup premium de produto.*

## 2. ✅ `dor-caderninho.jpg` — Seção Dor/Solução (já gerada e aplicada)

> Photorealistic image of a stressed Brazilian salon owner at a reception desk, surrounded by a messy paper notebook, sticky notes and a calculator, salon interior in the background, warm natural lighting, shallow depth of field, candid editorial photography style, no readable text

*Tradução: foto realista de uma dona de salão brasileira estressada na recepção, cercada por um caderno bagunçado, post-its e uma calculadora, interior do salão ao fundo, luz natural quente, profundidade de campo rasa, estilo fotografia editorial espontânea.*

## 3. ✅ `agenda-online.jpg` — Destaque Agenda Online (já gerada e aplicada)

> Photorealistic image of a smiling young Brazilian woman sitting on a couch at home, booking a beauty appointment on her smartphone, soft cozy lighting, the phone screen shows an abstract blue and white booking app interface with no readable text, lifestyle photography, shallow depth of field

*Tradução: foto realista de uma jovem brasileira sorrindo, sentada no sofá de casa, agendando um horário de beleza pelo celular, luz suave e aconchegante, tela do celular com interface abstrata azul e branca de app de agendamento sem texto legível, fotografia lifestyle.*

## 4. ⚠️ `perfil-individual.png` — Card "Profissional individual" (800x600, 4:3) — REGERAR: o download veio com a cena da agenda online duplicada

> Photorealistic image of a confident Brazilian nail designer working on a client's manicure in a small bright home studio, organized workspace with nail polish bottles, warm natural light, professional and welcoming atmosphere, editorial photography

*Tradução: foto realista de uma nail designer brasileira confiante fazendo a manicure de uma cliente em um pequeno estúdio iluminado, espaço organizado com vidros de esmalte, luz natural quente, atmosfera profissional e acolhedora.*

## 5. ✅ `perfil-salao.jpg` — Card "Salão ou barbearia" (já gerada e aplicada)

> Photorealistic image of a modern Brazilian beauty salon interior with a small team of hairdressers and barbers attending clients, mirrors and styling chairs, bright and clean space with subtle blue decor accents, lively professional atmosphere, editorial photography, wide shot

*Tradução: foto realista do interior de um salão de beleza brasileiro moderno com uma pequena equipe de cabeleireiros e barbeiros atendendo clientes, espelhos e cadeiras, espaço claro e limpo com detalhes decorativos azuis sutis, atmosfera profissional animada, plano aberto.*

## 6. ✅ `perfil-rede.jpg` — Card "Rede de lojas" (já gerada e aplicada)

> Photorealistic image of a Brazilian businesswoman holding a tablet, standing in front of a modern beauty salon storefront on a commercial street, the tablet shows an abstract blue dashboard with charts and no readable text, confident posture, daylight, editorial photography

*Tradução: foto realista de uma empresária brasileira segurando um tablet, em frente à fachada de um salão moderno em uma rua comercial, o tablet mostra um dashboard azul abstrato com gráficos e sem texto legível, postura confiante, luz do dia.*

## 7. `og-cover.png` — Open Graph / compartilhamento (1200x630)

> Wide marketing banner background, dark navy blue gradient with a large glowing cobalt blue letter M shape on the right side, floating smartphone showing an abstract calendar app interface, subtle geometric grid pattern, premium SaaS landing page aesthetic, empty space on the left for text overlay, no readable text

*Tradução: fundo de banner de marketing largo, gradiente azul-marinho escuro com uma grande letra M azul-cobalto brilhante à direita, smartphone flutuante mostrando interface abstrata de calendário, padrão geométrico sutil, estética premium de SaaS, espaço vazio à esquerda para sobrepor texto.*

**Dica:** sobreponha manualmente (Canva/Figma/editor) o logo e a frase "Menos trabalho manual. Mais controle." no espaço à esquerda — IA não gera texto confiável. Esta imagem só aparece quando o link do site é compartilhado (WhatsApp, redes sociais); a meta tag `og:image` no `index.html` precisa da URL absoluta final quando o domínio for definido.

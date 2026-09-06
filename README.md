# Proposta — Aniversário da Melissa · 6 anos

Página de proposta comercial da **Risotteria Suprema** para a festa de 24 de outubro de 2026, publicada via GitHub Pages para envio por link no WhatsApp.

**Link publicado:** https://alexregisdesouza-stack.github.io/proposta-melissa-6-anos/

---

## O que tem aqui

| Arquivo | Descrição |
|---|---|
| `index.html` | A proposta completa. Arquivo único, autocontido. |
| `README.md` | Este arquivo. |

O `index.html` não depende de nenhum outro arquivo do repositório. O logo está embutido em base64 e as únicas requisições externas são as fontes do Google Fonts.

## Seções da proposta

1. Capa com identificação do evento
2. Carta de apresentação do chef
3. Cadência do serviço ao longo da festa
4. Coquetel volante para adultos, em três tempos
5. Mesa Mágica das crianças
6. O que está incluso e o que não está
7. Investimento
8. Itens opcionais
9. Condições comerciais

## Como publicar

1. Criar repositório **público** com o nome `proposta-melissa-6-anos`
2. Subir o `index.html` em `github.com/alexregisdesouza-stack/proposta-melissa-6-anos/upload`
   *(repositório sem commits usa `/upload`, não `/upload/main`)*
3. **Settings → Pages → Branch: `main` → Save**
4. O link fica no ar em cerca de um minuto

## Como atualizar

Editar direto pelo navegador em `/edit/main/index.html`, ou subir a versão nova por `/upload/main` mantendo o mesmo nome de arquivo. A publicação leva de 30 a 60 segundos para propagar.

Se a alteração não aparecer, é cache do navegador — abrir em aba anônima ou adicionar `?v=2` ao final da URL.

## Notas técnicas

- Responsivo, desenhado a partir do mobile — a maioria dos clientes abre pelo WhatsApp
- `noindex, nofollow` no `<head>`: a página não é indexada por buscadores, só quem tem o link acessa
- Tipografia: Italiana, Cormorant Garamond e Jost
- Paleta construída sobre o bordô e o damasco da marca
- Entrada das seções por `IntersectionObserver`, com classe `.js` para evitar conteúdo invisível caso o JavaScript não carregue
- `prefers-reduced-motion` respeitado

---

**Risotteria Suprema** — Catering & Personal Chef
Alex Regis de Souza · Florianópolis / SC
www.risotteriasuprema.com.br

*Material comercial destinado ao cliente do evento. Valores e condições conforme a proposta publicada.*

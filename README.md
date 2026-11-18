# Biloba Events — demo de staging

Landing page estática da Biloba Events para revisão da cliente. Não tem instalação nem passo de build.

## Ficheiros

Os quatro primeiros têm de ficar juntos, na mesma pasta.

- `index.html` — a página completa (HTML, CSS e JavaScript no mesmo ficheiro).
- `hero.mp4` — o filme do topo da página, para computador e tablet (1280 × 720, cerca de 14 MB).
- `hero-mobile.mp4` — o mesmo filme, mais leve, para telemóvel (640 × 360, cerca de 4 MB).
- `hero-poster.jpg` — a imagem que aparece enquanto o filme carrega.
- `vercel.json` — diz ao Vercel para enviar `X-Robots-Tag: noindex, nofollow`, para o staging não aparecer no Google.

## Atualizar a demo

1. Substituir os ficheiros na branch `main` (no GitHub: Add file → Upload files, arrastar todos).
2. O Vercel publica sozinho em cerca de um minuto.

## Publicar pela primeira vez no Vercel

1. Em vercel.com: Add New → Project → importar este repositório.
2. Framework Preset: Other. Deixar Build Command e Output Directory vazios.
3. Deploy.

## Estado (18 de novembro de 2026)

- Filme do topo: enviado pela cliente, cortado dos 5 s aos 117 s (sem o título inicial nem o cartão de logos final), sem som, em loop.
- Fotografias de banco de imagens (Unsplash), temporárias. Carregam diretamente do Unsplash.
- O formulário valida os campos mas não envia nada.
- Email: contact@bilobaevents.com. Telefone, WhatsApp e Instagram ainda são os da Marie in Lisbon, até chegar o número novo.
- Fonte de títulos: Inter Tight, até existir licença web da PP Neue Montreal.
- O site final é reconstruído em WordPress depois de a demo ser aprovada.

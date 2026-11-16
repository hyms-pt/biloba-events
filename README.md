# Biloba Events — demo de staging

Landing page estática da Biloba Events para revisão da cliente. É um único ficheiro, `index.html`, sem instalação nem passo de build.

## Ficheiros

- `index.html` — a página completa (HTML, CSS e JavaScript no mesmo ficheiro).
- `vercel.json` — diz ao Vercel para enviar `X-Robots-Tag: noindex, nofollow`, para o staging não aparecer no Google.

## Atualizar a demo

1. Substituir o `index.html` na branch `main`.
2. O Vercel publica sozinho em cerca de um minuto.

## Publicar pela primeira vez no Vercel

1. Em vercel.com: Add New → Project → importar este repositório.
2. Framework Preset: Other. Deixar Build Command e Output Directory vazios.
3. Deploy.

## Estado

- Fotografias de banco de imagens (Unsplash), temporárias. Carregam diretamente do Unsplash.
- O formulário valida os campos mas não envia nada.
- Email e Instagram são os da Marie in Lisbon, por confirmar.
- Fonte de títulos: Inter Tight, até existir licença web da PP Neue Montreal.
- O site final é reconstruído em WordPress depois de a demo ser aprovada.

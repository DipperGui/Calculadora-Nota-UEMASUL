# Calcula Nota (GitHub Pages)

## Seu ícone
1. Salve a imagem como **icon.png** (PNG quadrado, 1024x1024, sem transparência e sem cantos arredondados).
2. Substitua o arquivo `icon.png` desta pasta por ele. Mantenha exatamente esse nome.

O código já aponta para `icon.png` em dois lugares:
- `index.html`, nas linhas `<link rel="icon" ...>` e `<link rel="apple-touch-icon" ...>`
- `manifest.webmanifest`, no campo `"src": "icon.png"`

## Publicar
1. Crie um repositório no GitHub e envie os 3 arquivos (`index.html`, `manifest.webmanifest`, `icon.png`) na raiz.
2. Settings > Pages > Branch `main` / pasta `/ (root)` > Save.
3. Abra o link no Safari do iPhone > Compartilhar > Adicionar à Tela de Início.

Se o ícone não mudar, apague o app da tela inicial e adicione de novo (o iOS guarda o ícone antigo).

## Eventos (planilha do Google)
A aba Eventos lê a planilha publicada na web como CSV. O link fica no `index.html`, na constante `EVENTS_URL`. Se trocar de planilha, troque só esse link.
Colunas: `id, data, hora, titulo, tipo, local, descricao, link, status` (status: confirmado, à confirmar ou cancelado). A cor de cada tipo é automática.

# JP7 Parts — site

Página única (link na bio) da JP7 Parts, hospedada em **jp7parts.com.br**.
Site 100% estático: apenas `index.html` com HTML + CSS, sem framework e sem build.

## O que tem na página
- Logo centralizado no topo.
- Botão para a loja no **Mercado Livre**.
- Botão para a loja na **Shopee**.

## Como alterar

- **Trocar os links das lojas:** edite os `href` dos dois botões em `index.html`.
- **Adicionar o logo:** envie um arquivo chamado `logo.png` (ou `logo.svg`, ajustando
  o `src` no HTML) para a raiz do repositório. Recomendado: PNG com fundo transparente,
  ~500px de largura. Enquanto o arquivo não existir, o site mostra o texto "JP7 PARTS"
  como fallback automático.

## Deploy (Vercel)

Não há etapa de build. Basta importar este repositório na Vercel
(Framework Preset: **Other**, Build Command e Output Directory vazios). Detalhes de
domínio e DNS estão descritos no passo a passo entregue junto a este projeto.

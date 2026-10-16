# Leva, miga! Achados

Loja de achadinhos com ofertas da Shopee, Amazon, Mercado Livre e Magalu, de todas as categorias.

- `index.html` — o site inteiro, num arquivo só.
- As ofertas ficam no Supabase (tabelas `site_items` e `site_settings`) e são enviadas sozinhas pelo sistema **Viver Ofertas** (aba **Vitrine do site**), de tempos em tempos.
- O site só **lê** as ofertas com a chave pública. Só o sistema consegue alterar, com a chave secreta que fica no PC.
- Para mudar regras, categorias, aparência, fixar ou esconder produtos: use a aba **Vitrine do site** no sistema.

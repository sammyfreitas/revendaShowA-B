# RevendaShowA+B

Site one page simples, com:
- catálogo por categoria;
- carrinho;
- pedido por WhatsApp;
- aviso de Pix;
- retirada na Tijuca ou entrega por Uber/99;
- área local para controlar estoque;
- registro e exportação de vendas em CSV.

## Configuração rápida

1. Abra `app.js`.
2. Troque:
   `const WHATSAPP_NUMBER = "5521999999999";`
   pelo número real com DDD e somente números.
3. Para mudar o PIN da área de estoque, altere:
   `const ADMIN_PIN = "1234";`
4. Abra `index.html` no navegador.

## Publicação

Pode ser publicado gratuitamente no GitHub Pages, Netlify ou Vercel.

## Observação importante

A página foi marcada como revenda independente. Antes de publicar, confirme se você tem autorização para usar logotipo, imagens e identidade visual oficial da Cacau Show. O projeto usa uma identidade própria em tons de chocolate para reduzir o risco de parecer um canal oficial.


## Correção importante

Os produtos agora ficam incorporados diretamente no `app.js`. Assim, a lista aparece mesmo quando o `index.html` é aberto diretamente com duplo clique, sem servidor local.


## GitHub Pages

Repositório informado:
sammyfreitas/revendaShowA+B

Endereço do site:
https://sammyfreitas.github.io/revendaShowA+B/

## Carrinho

O carrinho agora sempre inicia vazio quando a página é carregada ou atualizada.
Ele não é mais salvo no localStorage.

## Estoque e JSON

As alterações feitas na área de estoque ficam salvas apenas no localStorage do navegador.
Um site estático hospedado no GitHub Pages não consegue reescrever o arquivo JSON do repositório.

Para alterar o estoque inicial para todos os visitantes, edite os valores no app.js
ou use um backend/banco de dados.

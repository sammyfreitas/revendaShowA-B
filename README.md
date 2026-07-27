## 🍫 RevendaShowA+B   
Site de catálogo e pedidos de chocolates, trufas e presentes com atendimento na Tijuca.   
    
![Site](https://img.shields.io/badge/Acessar%20o%20site-GitHub%20Pages-3c2118?style=for-the-badge)
![Instagram](https://img.shields.io/badge/Instagram-@revendaShowAB-E4405F?style=for-the-badge&logo=instagram&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-(21)%2096455--4310-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
    
### Sobre o projeto
A RevendaShowA+B é uma página de revenda independente com catálogo, seleção de sabores, controle de quantidade, carrinho e envio do pedido pelo WhatsApp.
O projeto funciona apenas com HTML, CSS e JavaScript, sem backend.  
   
### Funcionalidades
- Catálogo organizado por categorias;
- Carrossel de destaques;
- Escolha de sabor e quantidade;
- Carrinho com valor unitário, subtotal e total;
- Pedido formatado automaticamente para o WhatsApp;
- Pagamento informado via Pix;
- Retirada na Tijuca ou entrega por Uber/99 solicitada pelo comprador;
- Área administrativa protegida por PIN;
- Controle de estoque local;
- Registro local de vendas;
- Exportação das vendas em CSV e JSON;
- Exportação e importação do estoque em JSON;
- Layout responsivo para computador e celular.

### Como funciona o armazenamento
Os dados administrativos são armazenados no `localStorage` do navegador.
Isso permite usar o sistema sem servidor, mas significa que:
cada navegador possui seu próprio estoque e histórico;
as alterações não modificam automaticamente o código do GitHub;
limpar os dados do navegador apaga os dados locais;
é importante exportar periodicamente os arquivos JSON.
Estoque
Na área administrativa é possível:
ajustar as quantidades;
exportar o estoque atual em JSON;
importar novamente um JSON de estoque;
restaurar o estoque inicial definido no JavaScript.
Vendas
Cada venda registrada contém:
identificador;
data e hora;
produtos;
opções ou sabores;
quantidades;
valores;
total da venda.
O histórico pode ser exportado em:
`CSV`, para abrir no Excel;
`JSON`, para backup ou processamento futuro.

### Estrutura do projeto
```text
├── index.html
├── styles.css
├── app.js
├── README.md
└── assets/
    ├── logo-revendashowab.svg
    ├── favicon-cacau.svg
    └── imagens dos produtos
   
```
Executar localmente
Baixe o projeto e abra o arquivo `index.html` no navegador.
Também é possível usar a extensão Live Server no VS Code.
Publicação no GitHub Pages

### Repositório:
```text
sammyfreitas/revendaShowA+B
```
### Site:
```text
https://sammyfreitas.github.io/revendaShowA+B/
```

### Contato
Instagram: @revendaShowAB   
WhatsApp: (21) 96455-4310   
Email: revendashowAB@gmail.com   
Localização: Tijuca, RJ   

Aviso: Este é um site de Revenda Oficial da CacauShow, no entanto, não é o site oficial da marca.

---
Todos os direitos reservados — RevendaShowA+B  
Site desenvolvido por Anthony Freitas.

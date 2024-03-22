# Burguer-Dev

Ele é um exemplo simples de como criar um carrinho de compras usando JavaScript e o framework CSS Tailwind.

O projeto consiste em dois arquivos:

index.html: Este é o arquivo HTML que contém o layout da página. Ele inclui um menu com alguns itens e um botão para abrir o carrinho de compras. Quando um item do menu é clicado, a função addToCart é chamada com o nome e o preço do item como parâmetros. Essa função adiciona o item ao carrinho de compras ou aumenta a quantidade do item se ele já estiver no carrinho. Em seguida, a função updateCartModal é chamada para atualizar o conteúdo do carrinho de compras. O arquivo HTML inclui também as referências aos arquivos CSS do Tailwind para estilizar a página.
script.js: Este é o arquivo JavaScript que contém as funções addToCart e updateCartModal. A função addToCart adiciona o item ao carrinho de compras ou aumenta a quantidade do item se ele já estiver no carrinho. A função updateCartModal atualiza o conteúdo do carrinho de compras exibindo os itens e suas quantidades e preços. Além disso, o arquivo JavaScript define um event listener para o botão "Remover" que remove o item do carrinho de compras quando é clicado.

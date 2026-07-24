<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delícias no Pote</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>🍰 Delícias no Pote</h1>
    <p>O sabor caseiro que adoça o seu dia!</p>
</header>

<main>

<h2>Nosso Cardápio</h2>

<div class="produto">
    <h3>Bolo de Pote</h3>
    <p>R$ 10,00</p>
    <button onclick="adicionarCarrinho('Bolo de Pote',10)">
        + Adicionar ao Carrinho
    </button>
</div>

<div class="produto">
    <h3>Fatia de Bolo</h3>
    <p>R$ 8,00</p>
    <button onclick="adicionarCarrinho('Fatia de Bolo',8)">
        + Adicionar ao Carrinho
    </button>
</div>

<div class="produto">
    <h3>Mungunzá com Paçoca</h3>
    <p>R$ 12,00</p>
    <button onclick="adicionarCarrinho('Mungunzá com Paçoca',12)">
        + Adicionar ao Carrinho
    </button>
</div>

<h2>🛒 Carrinho</h2>

<ul id="carrinho"></ul>

<h3>Total: R$ <span id="total">0.00</span></h3>

<h2>Dados do Cliente</h2>

<input type="text" id="nome" placeholder="Seu nome">

<input type="tel" id="telefone" placeholder="Telefone">

<textarea id="observacao" placeholder="Observações"></textarea>

<button onclick="enviarPedido()">
    Fazer Pedido
</button>

</main>

<script src="script.js"></script>

</body>
</html>

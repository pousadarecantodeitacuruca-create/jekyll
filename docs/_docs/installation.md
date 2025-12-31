<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Burger Lab | Cardápio</title>
    <style>
        :root {
            --primary: #ffc107;
            --dark: #1a1a1a;
            --light: #f4f4f4;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--dark);
            color: var(--white);
            margin: 0;
            padding-bottom: 50px;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1571091718767-18b5b1457add?ixlib=rb-1.2.1&auto=format&fit=crop&w=1352&q=80');
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 60px 20px;
        }

        .container {
            max-width: 600px;
            margin: auto;
            padding: 20px;
        }

        h1 { color: var(--primary); margin-bottom: 10px; }
        
        .categoria {
            margin-top: 30px;
            border-bottom: 2px solid var(--primary);
            padding-bottom: 5px;
            text-transform: uppercase;
        }

        .item {
            background: #2a2a2a;
            margin: 15px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: 0.3s;
        }

        .item:hover { transform: scale(1.02); }

        .detalhes { flex: 1; }
        .nome { font-weight: bold; font-size: 1.1em; color: var(--primary); }
        .descricao { font-size: 0.9em; color: #ccc; margin-top: 5px; }
        .preco { font-weight: bold; margin-left: 15px; min-width: 70px; text-align: right; }

        .btn-whatsapp {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #25d366;
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body>

<header>
    <h1>🍔 BURGER LAB</h1>
    <p>O melhor blend da cidade direto na sua mesa.</p>
</header>

<div class="container">
    <h2 class="categoria">Burgers Artesanais</h2>
    
    <div class="item">
        <div class="detalhes">
            <div class="nome">Classic Burger</div>
            <div class="descricao">Pão brioche, blend 160g, queijo prato e maionese.</div>
        </div>
        <div class="preco">R$ 28,00</div>
    </div>

    <div class="item">
        <div class="detalhes">
            <div class="nome">Bacon Blast</div>
            <div class="descricao">Muita crocância com bacon caramelizado e cheddar.</div>
        </div>
        <div class="preco">R$ 34,00</div>
    </div>

    <h2 class="categoria">Acompanhamentos</h2>

    <div class="item">
        <div class="detalhes">
            <div class="nome">Batata Rústica</div>
            <div class="descricao">Temperada com alecrim e páprica defumada.</div>
        </div>
        <div class="preco">R$ 18,00</div>
    </div>

    <h2 class="categoria">Bebidas</h2>

    <div class="item">
        <div class="detalhes">
            <div class="nome">Soda Artesanal</div>
            <div class="descricao">Frutas vermelhas ou Limão siciliano.</div>
        </div>
        <div class="preco">R$ 12,00</div>
    </div>
</div>

<a href="https://wa.me/LARICA'SBURGER" class="btn-whatsapp" target="_blank">
    Pedir pelo WhatsApp 📱
</a>

</body>
</html>

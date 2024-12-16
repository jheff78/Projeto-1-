# Projeto-1-
Um projeto a HTML 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos na Europa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #0078d7;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            margin: 15px 0;
            display: flex;
            flex-wrap: wrap;
        }
        .card img {
            width: 100%;
            max-width: 400px;
            object-fit: cover;
        }
        .card-content {
            padding: 15px;
            flex: 1;
        }
        .card h3 {
            margin: 0 0 10px;
            color: #0078d7;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #0078d7;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Explore os Destinos Mais Famosos da Europa</h1>
    <p>Descubra os lugares que fazem da Europa um continente inesquecível.</p>
</header>

<div class="container">

    <div class="card">
        <img src="https://via.placeholder.com/400" alt="Torre Eiffel, Paris">
        <div class="card-content">
            <h3>Torre Eiffel - Paris, França</h3>
            <p>Um dos monumentos mais icônicos do mundo, a Torre Eiffel é uma parada obrigatória para quem visita Paris. 
            Aproveite a vista panorâmica do topo e explore os arredores cheios de charme.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/400" alt="Coliseu, Roma">
        <div class="card-content">
            <h3>Coliseu - Roma, Itália</h3>
            <p>O Coliseu é uma das sete maravilhas do mundo e um símbolo da história romana. Conheça a fascinante 
            história dos gladiadores e do Império Romano neste incrível anfiteatro.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/400" alt="Santorini, Grécia">
        <div class="card-content">
            <h3>Santorini - Grécia</h3>
            <p>Com suas casas brancas e cúpulas azuis, Santorini é um destino de sonho. Aproveite o pôr do sol espetacular, 
            as praias vulcânicas e a deliciosa gastronomia grega.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/400" alt="Palácio de Westminster, Londres">
        <div class="card-content">
            <h3>Palácio de Westminster e Big Ben - Londres, Reino Unido</h3>
            <p>Um dos cartões-postais de Londres, o Palácio de Westminster e seu famoso relógio, o Big Ben, são imperdíveis. 
            Explore o charme histórico e cultural dessa cidade incrível.</p>
        </div>
    </div>

</div>

<footer>
    <p>© 2024 Descubra a Europa | Criado com ❤️ para viajantes</p>
</footer>

</body>
</html>

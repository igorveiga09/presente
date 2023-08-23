<!DOCTYPE html>
<html>
<head>
    <title>Vale presente</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
        }
        
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #3498db;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Vc ganhou um presente, clique aqui para receber</h1>
    <button id="pedidoButton">Aperte aqui!</button>
    <p id="resposta" style="display: none;"></p>

    <script>
        const pedidoButton = document.getElementById('pedidoButton');
        const resposta = document.getElementById('resposta');
        
        pedidoButton.addEventListener('click', () => {
            resposta.style.display = 'block';
            resposta.textContent = 'Parabéns mo, vc ganhou um vale banho! :) 💖';
            pedidoButton.style.display = 'none';
        });
    </script>
</body>
</html>

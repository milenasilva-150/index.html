# index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Primeiro Teste</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f2f5;
            padding-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Olá, Mundo! 🚀</h1>
    <p>Este é o meu primeiro código rodando no computador.</p>
    
    <!-- Botão que exibe uma mensagem quando clicado -->
    <button onclick="clicou()">Clique em mim!</button>

    <script>
        function clicou() {
            alert("Parabéns! O código funcionou perfeitamente!");
        }
    </script>

</body>
</html>

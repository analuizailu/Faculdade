<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Calculadora de IMC</title>
</head>
<body>
    <div class="container">
        <h1>Calculadora de IMC</h1>
        <form id="imc-form">
            <div class="input-group">
                <label for="peso">Peso (kg):</label>
                <input type="number" id="peso" placeholder="Digite seu peso" required>
            </div>
            <div class="input-group">
                <label for="altura">Altura (m):</label>
                <input type="number" step="0.01" id="altura" placeholder="Digite sua altura" required>
            </div>
            <button type="button" id="calcular">Calcular</button>
            <button type="reset" id="resetar">Resetar</button>
        </form>
        <div id="resultado" class="resultado"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>


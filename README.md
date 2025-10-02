<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estructura de Tycoon - Solo HTML</title>
    <style>
        /* CSS para hacerlo parecer un poco más un juego. Esto NO es programación. */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #6f4e37; /* Color café */
            text-align: center;
        }
        .stats, .upgrades {
            border: 1px solid #ddd;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 6px;
        }
        .stats p {
            font-size: 1.1em;
            margin: 5px 0;
        }
        .upgrades h2 {
            color: #8b4513; /* Color marrón */
            border-bottom: 2px solid #8b4513;
            padding-bottom: 5px;
            margin-top: 0;
        }
        .upgrade-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 0;
            border-bottom: 1px dashed #eee;
        }
        .upgrade-item:last-child {
            border-bottom: none;
        }
        .buy-button {
            background-color: #6f4e37;
            color: white;
            padding: 8px 15px;
            border: none;
            border-radius: 4px;
            cursor: default; /* Indicamos que NO es funcional */
        }
    </style>
</head>
<body>

<div class="container">
    <h1>☕ Tycoon de la Cafetería ☕</h1>
    
    <div class="stats">
        <h2>💰 Estado Financiero</h2>
        <p><strong>Monedas:</strong> <span id="monedas">1,250.75</span></p>
        <p><strong>Ganancia por Segundo:</strong> <span id="gps">15.50</span></p>
        <p><strong>Clientes Atendidos:</strong> <span id="clientes">587</span></p>
    </div>
    
    <div class="upgrades">
        <h2>🚀 Inversiones y Mejoras</h2>

        <div class="upgrade-item">
            <div>
                <h3>Comprar Tostadora Automática</h3>
                <p>Aumenta la ganancia por segundo en +5.00.</p>
            </div>
            <button class="buy-button">Comprar ($500.00)</button>
        </div>

        <div class="upgrade-item">
            <div>
                <h3>Contratar Barista Experto</h3>
                <p>Reduce el tiempo de preparación, aumenta la ganancia en +10.00.</p>
            </div>
            <button class="buy-button">Comprar ($1,500.00)</button>
        </div>

        <div class="upgrade-item">
            <div>
                <h3>Abrir Sucursal (x2 Ganancia)</h3>
                <p>Duplica tu ganancia pasiva actual.</p>
            </div>
            <button class="buy-button">Comprar ($5,000.00)</button>
        </div>
        
    </div>

    <p style="text-align: center; color: red;">
        ⚠️ **AVISO:** Este código es SOLO la estructura visual (HTML/CSS). Para que los números cambien y los botones funcionen, necesitarías **JavaScript**.
    </p>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Marc-Tech Obfuscator</title>
    <style>
        body {
            background-color: #000;
            color: #00FF00;
            font-family: 'Courier New', monospace;
            padding: 20px;
        }

        textarea, input[type="submit"] {
            background-color: #111;
            color: #00FF00;
            border: 1px solid #00FF00;
            padding: 10px;
            width: 100%;
            margin-top: 10px;
        }

        h1, h2 {
            color: #00FF00;
        }

        .footer {
            margin-top: 40px;
            font-size: 12px;
            color: #00aa00;
            text-align: center;
        }

        pre {
            background-color: #111;
            padding: 10px;
            overflow-x: auto;
        }
    </style>
</head>
<body>

    <h1>Marc-Tech PHP Obfuscator</h1>
    <p>Collez votre code PHP ci-dessous pour l'obfusquer automatiquement.</p>

    <form method="POST">
        <textarea name="phpCode" rows="10" placeholder="Entrez ici votre code PHP..."><?php echo isset($_POST['phpCode']) ? htmlspecialchars($_POST['phpCode']) : ''; ?></textarea>
        <input type="submit" value="Obfusquer le code">
    </form>

    <?php
    if ($_SERVER['REQUEST_METHOD'] == 'POST' && !empty($_POST['phpCode'])) {
        $phpCode = $_POST['phpCode'];

        $ch = curl_init();
        curl_setopt($ch, CURLOPT_URL, 'https://xboo-protector.p.rapidapi.com/_API_MASHAPE/obfuscator_php/?return=base64_encode&protection=v2');
        curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
        curl_setopt($ch, CURLOPT_POST, true);
        curl_setopt($ch, CURLOPT_POSTFIELDS, http_build_query(['codes' => $phpCode]));
        curl_setopt($ch, CURLOPT_HTTPHEADER, [
            'Content-Type: application/x-www-form-urlencoded',
            'data_type: normal',
            'x-rapidapi-host: xboo-protector.p.rapidapi.com',
            'x-rapidapi-key: ab42dda446mshde4ba65d25b85fdp13b83ejsn3965c0519b7d' // ta clé API ici
        ]);

        $response = curl_exec($ch);
        curl_close($ch);

        echo '<h2>Code Obfusqué :</h2>';
        echo '<pre>' . htmlspecialchars($response) . '</pre>';
    }
    ?>

    <div class="footer">
        &copy; 2025 Marc-Tech. Tous droits réservés. Obfuscation automatique de scripts PHP.
    </div>

</body>
</html>

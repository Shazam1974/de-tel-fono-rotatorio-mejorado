<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manuel Ramírez - El Despertar y la Música</title>
    <style>
        body {
            background-color: #0a0a0a;
            color: #ffffff;
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .container {
            padding: 40px 20px;
            max-width: 900px;
        }
        h1 {
            font-size: 2.8rem;
            margin-bottom: 5px;
            background: linear-gradient(to right, #fff, #888);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .quote {
            font-style: italic;
            font-size: 1.3rem;
            border-left: 4px solid #00ff88;
            padding: 15px;
            margin: 40px 0;
            background: #111;
            border-radius: 0 15px 15px 0;
        }
        .grid-links {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .btn {
            display: block;
            padding: 20px;
            text-decoration: none;
            color: white;
            border-radius: 12px;
            font-weight: bold;
            transition: transform 0.3s, background 0.3s;
            border: 1px solid rgba(255,255,255,0.1);
        }
        .btn:hover { transform: scale(1.05); }
        .youtube { background: #ff0000; }
        .suno { background: #6a1b9a; }
        .facebook { background: #1877f2; }
        
        .success-box {
            margin-top: 40px;
            background: #1a1a1a;
            padding: 20px;
            border-radius: 15px;
            border: 1px solid #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Manuel Ramírez Preza</h1>
        <p style="color: #00ff88; letter-spacing: 2px;">CREADOR • COMPOSITOR • CONCIENCIA</p>

        <div class="quote">
            "Todo lo que creía era una mentira... hoy actúo con justicia y merecimiento. <br>
            Soy el único responsable de cómo imagino vivir en este plano."
        </div>

        <div class="success-box">
            <h3>Éxito Internacional</h3>
            <p>Proyectos musicales aceptados en <strong>USA y España</strong>.</p>
            <p>Fusionando la IA con la esencia de Guanajuato.</p>
        </div>

        <h2 style="margin-top: 50px;">Conecta con mi Obra</h2>
        <div class="grid-links">
            <a href="https://www.youtube.com/@ManuelRamirez-tp9wu" target="_blank" class="btn youtube">
                📺 Canal de YouTube
            </a>
            <a href="https://suno.com/@purposefulclavichords1167" target="_blank" class="btn suno">
                🎵 Escuchar en Suno
            </a>
            <a href="https://www.facebook.com/share/1AgnGujVDK/" target="_blank" class="btn facebook">
                👥 Comunidad Facebook
            </a>
        </div>

        <footer>
            <p style="margin-top: 80px; font-size: 0.8rem; color: #444;">
                &copy; 2025 Manuel Ramírez Preza. <br>
                Guanajuato, México para el mundo.
            </p>
        </footer>
    </div>
</body>
</html>

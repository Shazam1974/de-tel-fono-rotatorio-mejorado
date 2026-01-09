<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manuel Ramírez Preza - El Artista del Asfalto</title>
    <style>
        /* Animación del brillo en el nombre */
        @keyframes brillo-musical {
            0% { background-position: -200%; }
            100% { background-position: 200%; }
        }

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

        /* Nombre con efecto de luz */
        .titulo-animado {
            font-size: 2.8rem;
            margin-bottom: 5px;
            font-weight: bold;
            text-transform: uppercase;
            background: linear-gradient(90deg, #444, #fff, #444);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: brillo-musical 3s linear infinite;
            display: inline-block;
        }

        .stats-didi {
            color: #00ff88;
            font-size: 0.9rem;
            font-weight: bold;
            letter-spacing: 1px;
            margin: 15px 0;
        }

        .quote {
            font-style: italic;
            font-size: 1.3rem;
            border-left: 4px solid #00ff88;
            padding: 15px;
            margin: 40px 0;
            background: #111;
            border-radius: 0 15px 15px 0;
            text-align: left;
        }

        .grid-links {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
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
        .spotify { background: #1DB954; }
        .youtube { background: #ff0000; }
        .suno { background: #6a1b9a; }
        .facebook { background: #1877f2; }
        
        .success-box {
            margin-top: 40px;
            background: #1a1a1a;
            padding: 25px;
            border-radius: 15px;
            border: 1px solid #00ff88;
            box-shadow: 0 0 15px rgba(0, 255, 13
            

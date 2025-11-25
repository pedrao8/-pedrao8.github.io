# -pedrao8.github.io
trabalho dos links favoritos que eu mais uso no meu dia-dia
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Links Favoritos</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-image: url('https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=1920');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(0, 0, 0, 0.7);
            backdrop-filter: blur(10px);
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
        }

        h1 {
            color: white;
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .links-grid {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 30px;
            max-width: 900px;
        }

        .link-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-decoration: none;
            transition: transform 0.3s ease;
        }

        .link-item:hover {
            transform: translateY(-10px);
        }

        .icon-container {
            width: 80px;
            height: 80px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .link-item:hover .icon-container {
            background: rgba(255, 255, 255, 0.2);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.5);
        }

        .icon-container img {
            width: 50px;
            height: 50px;
            object-fit: contain;
        }

        .link-name {
            color: white;
            font-size: 14px;
            margin-top: 12px;
            opacity: 0;
            transform: translateY(-10px);
            transition: all 0.3s ease;
            text-align: center;
            font-weight: 500;
        }

        .link-item:hover .link-name {
            opacity: 1;
            transform: translateY(0);
        }

        @media (max-width: 768px) {
            .links-grid {
                grid-template-columns: repeat(3, 1fr);
                gap: 20px;
            }

            .container {
                padding: 30px;
            }

            h1 {
                font-size: 2em;
            }
        }

        @media (max-width: 480px) {
            .links-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Meus Links Favoritos</h1>
        <div class="links-grid">
            <a href="https://web.whatsapp.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
                </div>
                <span class="link-name">WhatsApp</span>
            </a>

            <a href="https://www.youtube.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/YouTube_full-color_icon_%282017%29.svg" alt="YouTube">
                </div>
                <span class="link-name">YouTube</span>
            </a>

            <a href="https://music.youtube.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Youtube_Music_icon.svg" alt="YouTube Music">
                </div>
                <span class="link-name">YouTube Music</span>
            </a>

            <a href="https://www.instagram.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
                </div>
                <span class="link-name">Instagram</span>
            </a>

            <a href="https://discord.com/app" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6a49cf127bf92de1e2_icon_clyde_blurple_RGB.png" alt="Discord">
                </div>
                <span class="link-name">Discord</span>
            </a>

            <a href="https://chat.openai.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" alt="ChatGPT">
                </div>
                <span class="link-name">ChatGPT</span>
            </a>

            <a href="https://mail.google.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Gmail">
                </div>
                <span class="link-name">Gmail</span>
            </a>

            <a href="https://www.plurall.net/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="data:image/png;base64,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" alt="Plurall">
                </div>
                <span class="link-name">Plurall</span>
            </a>

            <a href="https://classroom.google.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/5/59/Google_Classroom_Logo.png" alt="Google Classroom">
                </div>
                <span class="link-name">Google Classroom</span>
            </a>

            <a href="https://sofifa.com/" target="_blank" class="link-item">
                <div class="icon-container">
                    <img src="https://www.sportmonks.com/wp-content/uploads/2024/01/sofifa-logo.png" alt="Sofifa">
                </div>
                <span class="link-name">Sofifa</span>
            </a>
        </div>
    </div>
</body>
</html>

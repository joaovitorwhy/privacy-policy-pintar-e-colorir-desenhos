<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Política de Privacidade - Pintar e Colorir Desenhos</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Nunito', sans-serif;
      background: linear-gradient(180deg, #5B6CFF 0%, #7B61FF 100%);
      min-height: 100vh;
      color: white;
      padding: 40px 20px;
      overflow-x: hidden;
      position: relative;
    }

    body::before,
    body::after {
      content: '';
      position: absolute;
      border-radius: 50%;
      filter: blur(90px);
      opacity: 0.25;
      z-index: 0;
    }

    body::before {
      width: 300px;
      height: 300px;
      background: #ffffff;
      top: -100px;
      left: -100px;
    }

    body::after {
      width: 350px;
      height: 350px;
      background: #9D5CFF;
      bottom: -120px;
      right: -120px;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      position: relative;
      z-index: 1;
    }

    .card {
      background: rgba(255, 255, 255, 0.12);
      backdrop-filter: blur(18px);
      -webkit-backdrop-filter: blur(18px);
      border: 1px solid rgba(255,255,255,0.18);
      border-radius: 32px;
      padding: 40px;
      box-shadow: 0 12px 40px rgba(0,0,0,0.18);
    }

    .header {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-bottom: 30px;
    }

    .logo {
      width: 90px;
      height: 90px;
      border-radius: 24px;
      background: linear-gradient(135deg, #8B5CF6, #5B6CFF);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 42px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.2);
    }

    h1 {
      font-family: 'Fredoka', sans-serif;
      font-size: 42px;
      line-height: 1.1;
      margin-bottom: 8px;
      text-shadow: 0 4px 10px rgba(0,0,0,0.18);
    }

    .subtitle {
      font-size: 18px;
      opacity: 0.9;
    }

    .intro {
      margin-bottom: 35px;
      font-size: 18px;
      line-height: 1.8;
      color: rgba(255,255,255,0.95);
    }

    .section {
      margin-bottom: 30px;
      padding: 24px;
      border-radius: 24px;
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.08);
    }

    .section h2 {
      font-family: 'Fredoka', sans-serif;
      font-size: 28px;
      margin-bottom: 12px;
      color: #ffffff;
    }

    .section p {
      font-size: 17px;
      line-height: 1.8;
      color: rgba(255,255,255,0.92);
    }

    .contact-box {
      margin-top: 35px;
      padding: 26px;
      border-radius: 24px;
      background: linear-gradient(135deg, #00D9A6, #00C896);
      color: white;
      box-shadow: 0 10px 24px rgba(0,0,0,0.15);
    }

    .contact-box h3 {
      font-family: 'Fredoka', sans-serif;
      font-size: 28px;
      margin-bottom: 10px;
    }

    .contact-box a {
      color: white;
      text-decoration: none;
      font-weight: 700;
      font-size: 18px;
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      opacity: 0.75;
      font-size: 15px;
    }

    @media (max-width: 768px) {
      .card {
        padding: 24px;
        border-radius: 24px;
      }

      .header {
        flex-direction: column;
        align-items: flex-start;
      }

      h1 {
        font-size: 32px;
      }

      .section h2 {
        font-size: 24px;
      }

      .section p,
      .intro {
        font-size: 16px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="card">

      <div class="header">
        <div class="logo">🎨</div>

        <div>
          <h1>Política de Privacidade</h1>
          <p class="subtitle">Pintar e Colorir Desenhos • Última atualização: maio de 2026</p>
        </div>
      </div>

      <p class="intro">
        Esta Política de Privacidade explica como o aplicativo <strong>Pintar e Colorir Desenhos</strong> trata as informações dos usuários. Ao usar o aplicativo, você concorda com os termos descritos neste documento.
      </p>

      <div class="section">
        <h2>1. Coleta de Informações</h2>
        <p>
          O aplicativo não coleta, armazena nem transmite dados pessoais para servidores externos. Todas as informações geradas pelo uso do aplicativo ficam armazenadas exclusivamente no dispositivo do usuário, como desenhos criados e salvos pelo usuário e preferências de uso.
        </p>
      </div>

      <div class="section">
        <h2>2. Uso das Informações</h2>
        <p>
          As informações armazenadas localmente são usadas exclusivamente para exibir os desenhos salvos na galeria do aplicativo e permitir que o usuário continue editando desenhos anteriores.
        </p>
      </div>

      <div class="section">
        <h2>3. Compartilhamento de Dados</h2>
        <p>
          Não compartilhamos, vendemos, alugamos ou transferimos qualquer informação do usuário para terceiros. Nenhum dado é enviado para servidores, nuvem ou qualquer sistema externo.
        </p>
      </div>

      <div class="section">
        <h2>4. Serviços de Terceiros</h2>
        <p>
          O aplicativo não integra serviços de análise, publicidade ou rastreamento de terceiros.
        </p>
      </div>

      <div class="section">
        <h2>5. Crianças</h2>
        <p>
          O Pintar e Colorir Desenhos é um jogo voltado para crianças de todas as idades. Não coletamos nenhuma informação pessoal de crianças, não exibimos publicidade direcionada e não há comunicação online entre usuários. O aplicativo está em conformidade com a COPPA e legislações similares.
        </p>
      </div>

      <div class="section">
        <h2>6. Permissões</h2>
        <p>
          O aplicativo solicita permissão de armazenamento, necessária para salvar e carregar os desenhos no dispositivo. Nenhuma permissão é usada para fins além do funcionamento do aplicativo.
        </p>
      </div>

      <div class="section">
        <h2>7. Segurança</h2>
        <p>
          Como nenhum dado é transmitido para fora do dispositivo, o risco de exposição de informações é mínimo.
        </p>
      </div>

      <div class="section">
        <h2>8. Alterações nesta Política</h2>
        <p>
          Podemos atualizar esta Política periodicamente. Recomendamos revisar esta página regularmente.
        </p>
      </div>

      <div class="contact-box">
        <h3>📩 Contato</h3>
        <p>Em caso de dúvidas, entre em contato:</p>
        <br>
        <a href="mailto:joaovitorfranca49@gmail.com">joaovitorfranca49@gmail.com</a>
      </div>

      <div class="footer">
        © 2026 Pintar e Colorir Desenhos • Todos os direitos reservados
      </div>

    </div>
  </div>

</body>
</html>

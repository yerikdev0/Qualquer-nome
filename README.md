<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Como Criar um Site com GitHub Pages</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: linear-gradient(to right, #1a1a1a, #2e2e2e);
      color: #ffffff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4b0082;
      padding: 20px;
      text-align: center;
      box-shadow: 0 0 10px #00000088;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      animation: neon 2s infinite alternate;
    }
    @keyframes neon {
      from { text-shadow: 0 0 10px #fff; }
      to   { text-shadow: 0 0 20px #8a2be2, 0 0 30px #8a2be2; }
    }
    main {
      padding: 40px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #8a2be2;
      margin-top: 40px;
    }
    code {
      background: #333;
      padding: 2px 6px;
      border-radius: 4px;
      color: #00ffcc;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #aaa;
    }
    .step {
      background: #222;
      padding: 20px;
      border-left: 5px solid #8a2be2;
      margin-bottom: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px #00000088;
    }
  </style>
</head>
<body>

  <header>
    <h1>📢 Como Criar e Publicar um Site com GitHub Pages</h1>
  </header>

  <main>
    <div class="step">
      <h2>1️⃣ Crie um arquivo <code>index.html</code></h2>
      <p>Abra o Bloco de Notas (ou qualquer editor de texto) e cole um código HTML simples. Salve com o nome <code>index.html</code>.</p>
    </div>

    <div class="step">
      <h2>2️⃣ Crie um repositório no GitHub</h2>
      <p>Acesse <a href="https://github.com/new" target="_blank">https://github.com/new</a>, dê um nome ao repositório, deixe como público e clique em <strong>Create repository</strong>.</p>
    </div>

    <div class="step">
      <h2>3️⃣ Envie seu arquivo para o GitHub</h2>
      <p>Você pode usar o <a href="https://desktop.github.com/" target="_blank">GitHub Desktop</a> para subir seu <code>index.html</code>. Basta arrastar o arquivo para a pasta do repositório, dar commit e clicar em <strong>Push origin</strong>.</p>
    </div>

    <div class="step">
      <h2>4️⃣ Ative o GitHub Pages</h2>
      <p>No repositório, vá em <strong>Settings → Pages</strong>. Em <strong>Source</strong>, selecione <code>main</code> e a pasta <code>/(root)</code>. Clique em <strong>Save</strong>.</p>
    </div>

    <div class="step">
      <h2>✅ Pronto!</h2>
      <p>Seu site estará disponível em poucos segundos no link: <code>https://seu-usuario.github.io/nome-do-repositorio/</code></p>
    </div>
  </main>

  <footer>
    Feito com 💜 por Erik Brito Fonseca
  </footer>

</body>
</html>

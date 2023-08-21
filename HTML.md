<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Minha Loja</title>
</head>
<body>
  <div class="container">
    <div class="left-section">
      <div class="content">
        <h1>Bem-vindo à Minha Loja</h1>
        <p>Encontre produtos incríveis para você.</p>
        <button id="btn-cadastrar">Cadastrar</button>
      </div>
    </div>
    <div class="right-section">
      <img src="imagem.jpg" alt="Imagem da Loja">
    </div>
  </div>
  
  <div class="popup" id="popup">
    <div class="popup-content">
      <h2>Cadastrar</h2>
      <form id="cadastro-form">
        <label for="email">E-mail:</label>
        <input type="email" id="email" required>

        <label for="senha">Senha:</label>
        <input type="password" id="senha" required pattern="^(?=.*[A-Za-z])(?=.*\d)(?=.*[@$!%*#?&])[A-Za-z\d@$!%*#?&]{8,}$">
        <p>A senha deve ter 8 caracteres, letras, números e pelo menos um caractere especial.</p>

        <label for="cpfCnpj">CPF/CNPJ:</label>
        <input type="text" id="cpfCnpj" required>

        <label for="numeroCelular">Número de Celular:</label>
        <input type="text" id="numeroCelular" required pattern="^\d{2}\d{8,9}$">
        <p>O número de celular deve ter 2 dígitos de DDD e de 8 a 9 dígitos após o DDD.</p>

        <button type="submit">Cadastrar</button>
        <button id="btn-fechar">Fechar</button>
      </form>
    </div>
  </div>
  
  <script src="script.js"></script>
</body>
</html>

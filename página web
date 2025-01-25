<!DOCTYPE html>
<html>
<head>
  <title>Web App - Input e Mensagem</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f4f4f9;
    }

    .container {
      text-align: center;
      padding: 20px;
      background: #fff;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
    }

    .container h1 {
      margin-bottom: 20px;
    }

    .container input {
      padding: 10px;
      width: 100%;
      max-width: 300px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .container button {
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }

    .container button:hover {
      background-color: #0056b3;
    }

    .message {
      margin-top: 20px;
      font-size: 18px;
      color: #007bff;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Digite algo no campo abaixo:</h1>
    <input type="text" id="userInput" placeholder="Digite algo...">
    <button onclick="showMessage()">Mostrar Mensagem</button>
    <p class="message" id="message"></p>
  </div>

  <script>
    function showMessage() {
      const input = document.getElementById('userInput').value;
      const messageElement = document.getElementById('message');

      if (input.trim() !== '') {
        messageElement.textContent = `Você digitou: "${input}"`;
      } else {
        messageElement.textContent = '';
      }
    }
  </script>
</body>
</html>

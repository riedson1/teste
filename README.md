<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simulador de Lucro com Salgados</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #fff8f2;
      margin: 0;
      padding: 20px;
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background: #ffffff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #e96f3a;
    }
    .step {
      margin-bottom: 30px;
    }
    .highlight {
      background: #ffe3d4;
      padding: 15px;
      border-left: 5px solid #e96f3a;
      margin: 10px 0;
    }
    .saldo {
      font-size: 1.5em;
      font-weight: bold;
      color: green;
    }
    .button {
      background-color: #e96f3a;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 30px;
    }
    .button:hover {
      background-color: #d95b1a;
    }
  </style>
</head>
<body>

<div class="container">
  <h1>Você pode fazer dinheiro com as próprias mãos</h1>

  <div class="step">
    <h2>1. Você começa do zero</h2>
    <p class="highlight">Sem dinheiro, só com força de vontade. Saldo inicial: <strong>R$0,00</strong></p>
  </div>

  <div class="step">
    <h2>2. Compra dos materiais</h2>
    <p>Você investe em ingredientes, gás, embalagens...</p>
    <p class="highlight">Você gastou R$147,50 pra fazer 120 salgados.<br/>Saldo atual: <span class="saldo" style="color: red;">-R$147,50</span></p>
  </div>

  <div class="step">
    <h2>3. Produção dos salgados</h2>
    <p>Você produziu 120 salgados com custo unitário de R$1,22.</p>
  </div>

  <div class="step">
    <h2>4. Vendas</h2>
    <p>Você vendeu todas as unidades a R$3,50 cada.</p>
    <p class="highlight">Faturamento total: R$420,00<br/>Lucro: <span class="saldo">+R$272,50</span></p>
  </div>

  <div class="step">
    <h2>5. Recorrência</h2>
    <p>Você repete isso 3x por semana, com mais indicações, clientes fiéis...</p>
    <p class="highlight">Saldo acumulado no mês: <strong>R$5.434,00</strong></p>
  </div>

  <div class="step">
    <h2>Agora imagine isso com tudo pronto pra você…</h2>
    <p class="highlight">Cardápio validado, fornecedores confiáveis, estratégias testadas e plano de produção infalível.</p>
    <button class="button" onclick="window.location.href='https://seudominio.com/checkout'">
      Desbloquear acesso completo ao método
    </button>
  </div>
</div>

</body>
</html>

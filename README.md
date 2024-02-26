<html>

    <head>
	<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <title>
		
		 Abertura de Chamados de TI
		
		</title>
		
		<link rel="stylesheet" type="text/css" href="estilo.css">
			
</head>

<body> 
     
</html>
	  
  <head>
  </head>
  <style>
    *{
      font-family: Arial, sans-serif;
    }
    form{
      margin: 15px 5px;
      width: 500px;
      font-size: 16px;
    }
    form h1{
      text-align: center;
    }
    form label{
      display: block;
      margin-bottom: 5px;
    }
    form input, form textarea{
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
      box-sizing: border-box;
      resize: vertical;
    }
    form button{
      background: #4CAF50;
      color: white;
      padding: 10px 15px;
      margin-top: 5px;
      border: none;
      cursor: pointer;
    }
    form button:hover{
      background: green;
    }
  </style>
  <body>
    <form>
    
    <font color="#fff">

<h1>Abertura de Chamados de TI</h1>
	
    <form id="ticketForm">
       
        <label for="category">Setor:</label>
        <select id="category" name="category" required>
            <option value="hardware">Selecionar</option>
			<option value="hardware">showroom</option>
            <option value="software">Correntaria</option>
            <option value="software">Expedição</option>
            <option value="software">Estoque</option>
            <option value="software">Montagem</option>
			<option value="software">Auditório</option>
            <!-- Adicione outras categorias conforme necessário -->
        </select>
		
		<label for="category">Categoria:</label>
        <select id="category" name="category" required>
            <option value="hardware">Selecionar</option>
			<option value="hardware">Computador</option>
            <option value="software">Sistema</option>
            <option value="software">Impressora</option>
            <option value="software">Internet</option>
            <option value="software">Telefone</option>
            <!-- Adicione outras categorias conforme necessário -->
        </select>


    <form>
      <h1>Dados do Solicitante</h1>
      <label for="">Nome</label>
      <input type="text" class="name">

      <label for="">E-mail</label>
      <input type="text" class="email">

      <label for="">Data e Hora</label>
      <input type="text" class="country">

      <label for="">Descreva o Problema</label>
      <textarea class="message"></textarea>
      <button type="button" onclick="sendwhatsapp();">Abrir Chamado</button>
    </form>

    <script>
      function sendwhatsapp(){
       var phonenumber = "+5511933367506";


       var name = document.querySelector(".name").value;
       var email = document.querySelector(".email").value;
       var country = document.querySelector(".country").value;
       var message = document.querySelector(".message").value;

       var url = "https://api.whatsapp.com/send?phone=5511933367506&text=Ola%Chamado%TI" + phonenumber + "?text="
       +"*Name :* "+name+"%0a"
       +"*Email :* "+email+"%0a"
       +"*Country:* "+country+"%0a"
       +"*Message :* "+message
       +"%0a%0a"
       +"Uma nova abertuda de chamado,foi feita.";

       window.open(url, '_blank').focus();
     }
    </script>
  </body>
</html>
    
	<!DOCTYPE html>


<html lang="pt-br">


<head>
    
    
<meta charset="UTF-8">
    
<meta name="viewport" content="width=device-width, initial-scale=1.0">
        
<title>Sua Página</title>
      
<style>
        
        body {
            display: flex;
            justify-content: center; /* Centraliza horizontalmente */
            align-items: center; /* Centraliza verticalmente */
            height: 100vh; /* Define a altura da página como 100% da altura da viewport */
            margin: 0; /* Remove margens padrão */
        }

        .content {
            text-align: center; /* Centraliza o conteúdo dentro do elemento */
            width: 80%; /* Define a largura máxima do conteúdo */
        }
    </style>

</head
</head>
<body>
    
   
<div class="content">





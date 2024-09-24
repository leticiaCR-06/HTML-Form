<!DOCTYPE html>
<html>
<head>
    <style>
        form{
            border: 7px solid rgb(90, 88, 88);
            border-radius: 10px;
            padding-left: 10px;
            padding-top: 10px;
            margin: 20px;
            background-color: beige;
             }
    </style>
</head>
<body style="margin-right:200px; margin-top: 1px; padding: 50px; background-color: darkgray;">

<h1 style="text-align: center;">Formulário</h1>

 <form style="width:360px; height:280px;" method="get">
  <p><mark>Dados Pessoais(Nome, Gênero, Escolaridade):</mark></p>
<label style="border:1px; padding: 15px; border-style: inset;" for="fname;">NOME:</label>
<input  type="text" id="fname" name="fname" style="border:1px; padding: 15px; border-style: inset;"><br><br>


<label for="sexo;" style="border:1px; padding: 15px; border-style: inset;">SEXO:</label>
<input type="radio" id="sexo" name="sexo" value="Feminino">
  <label for="Feminino">Feminino</label>
<input type="radio" id="sexo" name="sexo" value="Masculino">
  <label for="Masculino">Masculino</label><br><br>


<label for="escolaridade" style="border:1px; padding: 15px; border-style: inset;">ESCOLARIDADE:</label>
  <select id="escolaridade" name="escolaridade" style="border:1px; padding: 15px; border-style: inset;">
    <option value="1grau">1° Grau</option>
    <option value="2grau">2° Grau</option>
    <option value="Superior">Superior</option>
  </select><br><br>
  
  <input type="submit" value="Submit">
 </form>

 <form style="width:490px; height:290px; float:right;" method="get">
  <p><mark>Pagamento/Dados do Cartão:</mark></p>
  <label style="border:1px; padding: 15px; border-style: inset;" for="fname;">Número:</label>
  <input  type="text" id="fname" name="fname" style="border:1px; padding: 15px; border-style: inset;"><br><br>
  
  
  <label for="sexo;" style="border:1px; padding: 15px; border-style: inset;">Bandeira:</label>
  <input type="radio" id="bandeira" name="bandeira" value="Visa">
    <label for="Visa"><img src="data:image/png;base64/"style="width:80px;height:80px;"></label>
  <input type="radio" id="bandeira" name="bandeira" value="Master">
    <label for="Master"><img src="data:image/png;base64,tsnmMevVgWNjiRLk9PGlrREgr11FvnSgNTog/" style="width: 80px; height: 80px;"></label>
  <input type="radio" id="bandeira" name="bandeira" value="American">
    <label for="American"><img src="data:image/png;base64,mWdRFF710spVnPeOp/" style="height: 80px; width: 80px;"></label><br><br>
  
  <label for="data" style="border:1px; padding: 15px; border-style: inset;">Validade:</label>
    <input type="date" id="data" name="Validade" style="height: 2px; padding: 10px;"><br><br>
    
    <input type="submit" value="Submit">
   
   </form>
  
</body>
</html>
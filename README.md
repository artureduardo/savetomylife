
<html> 
<head>
<title> VALIDAÇÃO DE E-MAIL </title>
</head>
<body>
<form name="form1" action="enviar.php" method="post">
Nome:
<input name="nome" type="text"><br /><br />
Email:
<input name="email" type="text"><br /><br />
Senha:
<input name="senha" type="password"><br /><br />
Repitir Senha:
<input name="rep_senha" type="password"><br /><br />
<input type="submit"  onclick="return validar()">
</form>
</body>
</html>
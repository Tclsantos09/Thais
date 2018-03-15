# Thais
<html>
	<head>
		<meta charset="utf-8">
		<script> 
		function deExemplo() 
			{
   			document.getElementById("exemplo").innerHTML = "Mentira.";
			}
		</script>
		
	</head>
	<body>
		<h3>Formulário</h3>
		<form action="new 1.asp" method="GET">
			<div>
				<label> Nome: </label>
				<input type="nome" id="nome" name="nome"/> <br>
			</div>
			<br>
			<div>
				<label> Email: </label>
				<input type="email" id="email" name="email"/> <br>
			</div>
			<br>
			<div>
				<label> Data: </label>
				<input type="date" id="data" name="data"/> <br>
			</div>
			<br>
			<div>
				<button type="submit"> Salvar </button>
			</div>
		</form>
		
			<form id="f1">
			<div>
			<br>
				<p id="exemplo">Palmeiras tem mundial.</p>
			<br>
			</div>
			
			<div>
				<button type="button" onclick="deExemplo()">Aperte para confirmar</button>
			</div>
			</form>
	</body>
</html>

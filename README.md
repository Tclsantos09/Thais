# Thais
<html>
	<head>
		<script> </script>
		<meta charset = "utf-8">
	</head>
	<body>
		<form id ="asp.asp" action="asp.asp" method="POST">
			<%
				for i = 0 to 9
					Response.Write("Valor: <input type=""text"" name=" & i & "><br>")
				Next
			%>
			<button type="submit"> salvar </button>
		</form>
	</body>
</html>

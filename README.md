# Thais
<html>
	<head>
		<script> </script>
		<meta charset = "utf-8">
	</head>
	<body>
		<form id ="9-03 asp.asp" action="9-03 asp.asp" method="POST">
			<%
				for i = 0 to 9
					Response.Write("Valor: <input type=""text"" name=" & i & "><br>")
				Next
			%>
			<button type="submit"> salvar </button>
		</form>
	</body>
</html>
	
Response.Write(Request(i))
	
	Dim vet(9)
	OMaior = 0
		For i = 0 to 9
			vet(i) = CLng(Request(i))
			n = vet(i)
				For j = 0 to 9
					If n > vet(j) Then
						If n > OMaior Then
							OMaior = n
						End if
                    End if
                Next
		Next
	Response.Write("Maior numero: " & OMaior)

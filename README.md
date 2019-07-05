# NVL-HTML-P10a
Estamos realizando una encuesta de satisfacción sobre un producto que hemos comprado. La empresa necesita conocer de la opinión de los usuarios a la hora de consumir eficientemente su producto.





<!DOCTYPE html>
<html>

<head> <meta charset="utf8">
	<title>Form defínete como persona</title>
</head>

<body style="background:#F5EEF8">
<form method="post" action="miservidor.php" width="50%" style="background:#D4EFDF">
	<fieldset style="border:2px solid #558B2F">
		<center>
			<legend><strong style="color:#0E6251">DEFINETE COMO PERSONA</strong></legend>
		</center>
		<p>
			<label> Nombre: <input type="text" name="Nombre" style="background:#F5EEF8"></label>
			<label> Primer Apellido: <input type="text" name="Primer Apellido" style="background:#F5EEF8"></label>
			<label> Segundo Apellido:<input type="text" name="Segundo Apellido" style="background:#F5EEF8"></label> </p>
	
		<p> <label> Edad: <input type="number" name="Edad" style="background:#F5EEF8"></label> </p>
	
		<p> <label> Lugar de nacimiento: <input type="text" name="Lugar de nacimiento" style="background:#F5EEF8"></label>
			<label> País de nacimiento: <select name:"País de nacimiento" style="background:#E1BEE7">
       <option value="ES">España</option>
        <option value="IT">Italia</option>
        <option value="FR">Francia</option>
     </select></label></p>
	
		<p> Sexo:
			<label> <input type="radio" name="Sexo" value="Masculino">Masculino</label>
			<label> <input type="radio" name="Sexo" value="Femenino">Femenino</label> </p>
	
		<p> <label> Número de hermanos: <select name="Número de hermanos" style="background:#E1BEE7"> 
        <option value="0">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        <option value="6">6</option>
        <option value="7">7</option>
        <option value="8">8</option>
     </select></label></p>
	
		<p>Comentario adicional:<br><textarea name="Comentario adicional" style="background:#F5EEF8"></textarea></p>
	</fieldset>
</form>
</body>


<input id=”Código Postal” name="cp" pattern="[\d]{5}(-[\d]{4})"/>



<!DOCTYPE html>
<html>

<head>
	<meta charset="utf8">
	<title>Satisfacción sobre un producto comprado</title>
</head>

<body style="background:#EBF5FB">
	<form method="post" action="miservnameor.php" style="background:#B3E5FC">

		<center>
			<legend>
				<h1 style="color:#7E57C2">ENCUESTA DE SATISFACCIÓN
					<h1>
			</legend>
		</center>
		<br></br>

		<fieldset style="border:2px solid #7E57C2">
			<legend style="color:#512DA8">
				<font size="4"><b>VALORE PRODUCTO Y SERVICIO</b></font>
			</legend>
			<br></br>
		
			<div style="color:#154360">
				<label for="Nivel de satisfacción">Puntué del 1 al 5 su nivel de satisfacción: </label>
				<input type="radio" name="Nivel de satisfacción" value="1">1
				<input type="radio" name="Nivel de satisfacción" value="2">2
				<input type="radio" name="Nivel de satisfacción" value="3">3
				<input type="radio" name="Nivel de satisfacción" value="4">4
				<input type="radio" name="Nivel de satisfacción" value="5">5
			</div>
			<br>

			<div style="color:#154360">
				<label for="Puntos positivos del producto">Por favor, indique que le gusta de nuestro producto: </label>
				<br>
				<textarea id="Puntos positivos del producto"></textarea>
			</div>
			<br>


			<div style="color:#154360">
				<label for="Puntos negativos del producto">Ayúdenos a mejorar. Describa que no le gusta: </label>
				<br>
				<textarea id="Puntos negativos del producto"></textarea>
			</div>
			<br>
            
			<div>
				<label for="Valoración Precio" style="color:#154360">Valore el precio: </label>
				<select id="Valoración Precio" style="background:#D2B4DE">
         <option value="Excelente">Excelente</option>
         <option value="Bueno">Bueno</option>
         <option value="Regular">Regular</option>
         <option value="Pésimo">Pésimo</option
       </select>
			</div>
			<br>

			<div>
				<label for="Valoración Producto" style="color:#154360">Califique la calidad de nuestro producto: </label>
				<select id="Valoración Producto" style="background:#D2B4DE">
         <option value="Excelente">Excelente</option>
         <option value="Bueno">Bueno</option>
         <option value="Regular">Regular</option>
         <option value="Pésimo">Pésimo</option
       </select>
			</div>
			<br>

			<div>
				<label for="Valoración Servicio Clientela" style="color:#154360">Califique nuestro Servicio Clientela: </label>
				<select id="Valoración Servicio Clientela" style="background:#D2B4DE">
         <option value="Excelente">Excelente</option>
         <option value="Bueno">Bueno</option>
         <option value="Regular">Regular</option>
         <option value="Pésimo">Pésimo</option
       </select>
			</div>
			<br>

			<div>
				<label for="Valoración Espera en la cola" style="color:#154360">Valore el tiempo de espera en la cola: </label>
				<select name="Valoración Espera en la cola" style="background:#D2B4DE">
         <option value="Excelente">Excelente</option>
         <option value="Bueno">Bueno</option>
         <option value="Regular">Regular</option>
         <option value="Pésimo">Pésimo</option
       </select>
			</div>
			<br>

		</fieldset>
		<br></br>

		<fieldset style="border:2px solid #7E57C2">
			<legend style="color:#512DA8">
                <font size="4"><b>INFORMACIÓN PERSONAL</b></font>
			</legend>

			<br>
			<div style="color:#154360">
				<label for="Código Postal">Código Postal: </label>
				<input id="Código Postal" type="postcode">
				<input type="submit" style="background:#D2B4DE">
            </div>
			<br>

			<div style="color:#154360">
				<label for="Mail">E-mail: </label>
				<input id="Mail" type="email">
				<input type="submit" style="background:#D2B4DE">
			</div>
			<br>

		</fieldset>
        <br></br>

        

        

		<center>
        	<div>	
				<input type="submit" style="background:#D2B4DE" value="Envieme" ><br></br>
         <font style="color:#512DA8"> Gracias por su colaboración <font>
			</div>
		<center>	

	

	</form>
</body>






<!DOCTYPE html>
<html>

<head>
	<meta charset="utf8">
	<title>Satisfacción sobre un producto comprado</title>
</head>

<body style="background:#EBF5FB">
	<form method="post" action="miservnameor.php" style="background:#B3E5FC">

		<center>
			<legend>
				<h1 style="color:#7E57C2">ENCUESTA DE SATISFACCIÓN
					<h1>
			</legend>
		</center>
		<br></br>

		<fieldset style="border:2px solid #7E57C2">
			<legend style="color:#512DA8">
				<font size="4"><b>VALORE PRODUCTO Y SERVICIO</b></font>
			</legend>
			<br></br>

			<div style="color:#154360">
				<label for="Valoración Precio">Puntué del 1 al 5 su nivel de satisfacción: </label>
				<input type="radio" name="Valoración Precio" value="1">1
				<input type="radio" name="Valoración Precio" value="2">2
				<input type="radio" name="Valoración Precio" value="3">3
				<input type="radio" name="Valoración Precio" value="4">4
				<input type="radio" name="Valoración Precio" value="5">5
			</div>
			<br>

			<div style="color:#154360">
				<label for="Puntos positivos del producto">Por favor, indique que le gusta de nuestro producto: </label>
				<br>
				<textarea id="Puntos positivos del producto"></textarea>
			</div>
			<br>


			<div style="color:#154360">
				<label for="Puntos negativos del producto">Ayúdenos a mejorar. Describa que no le gusta: </label>
				<br>
				<textarea id="Puntos negativos del producto"></textarea>
			</div>
			<br>



			<div style="color:#154360">
				<label for="Valoración Precio">Valore el precio: </label>
				<input type="radio" name="Valoración Precio" value="Excelente">Excelente
				<input type="radio" name="Valoración Precio" value="Bueno">Bueno
				<input type="radio" name="Valoración Precio" value="Regular">Regular
				<input type="radio" name="Valoración Precio" value="Pésimo">Pésimo

			</div>
			<br>


			<div style="color:#154360">
				<label for="Valoración Producto">Califique la calidad de nuestro producto: </label>
				<input type="radio" name="Valoración Producto" value="Excelente">Excelente
				<input type="radio" name="Valoración Producto" value="Bueno">Bueno
				<input type="radio" name="Valoración Producto" value="Regular">Regular
				<input type="radio" name="Valoración Producto" value="Pésimo">Pésimo

			</div>

			<br>

			<div style="color:#154360">
				<label for="Valoración Servicio Clientela">Califique nuestro Servicio Clientela: </label>
				<input type="radio" name="Valoración Servicio Clientela" value="Excelente">Excelente
				<input type="radio" name="Valoración Servicio Clientela" value="Bueno">Bueno
				<input type="radio" name="Valoración Servicio Clientela" value="Regular">Regular
				<input type="radio" name="Valoración Servicio Clientela" value="Pésimo">Pésimo
			</div>
			<br>

			<div style="color:#154360">
				<label for="Valoración Espera en la cola">Valore el tiempo de espera en la cola: </label>
				<input type="radio" name="Valoración Espera en la cola" value="Excelente">Excelente
				<input type="radio" name="Valoración Espera en la cola" value="Bueno">Bueno
				<input type="radio" name="Valoración Espera en la cola" value="Regular">Regular
				<input type="radio" name="Valoración Espera en la cola" value="Pésimo">Pésimo
			</div>
			<br>
		</fieldset>
		<br></br>

		<fieldset style="border:2px solid #7E57C2">
			<legend style="color:#512DA8">
				<font size="4"><b>INFORMACIÓN PERSONAL</b></font>
			</legend>

			<br>
			<div style="color:#154360">
				<label for="Código Postal">Código Postal: </label>
				<input id="Código Postal" type="postcode">
				<input type="submit" style="background:#D2B4DE">
			</div>
			<br>

			<div style="color:#154360">
				<label for="Mail">E-mail: </label>
				<input id="Mail" type="email">
				<input type="submit" style="background:#D2B4DE">
			</div>
			<br>

		</fieldset>
		<br></br>





		<center>
			<div>
				<input type="submit" style="background:#D2B4DE" value="Envieme"><br></br>
				<font style="color:#512DA8"> Gracias por su colaboración
					<font>
			</div>
			<center>



	</form>
</body>


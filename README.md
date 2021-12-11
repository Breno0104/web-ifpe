<!DOCTYPE html>
<html>
<head>
	<title>Formulario</title>
<style>
.caixa {
  font-size: 20px;
  width: 1200px;  
  height: 300px;
}

#nome{
	margin-left: 13.72%
}
#Sobrenome{
margin-left: 10%
}
#idade{
margin-left: 14%;
width: 35px;
}
#email{
margin-left: 13.6%
}

.TRE{
margin-left: 14.5%
}
#foto{
margin-left: 14.2%
}
#país{
	
}

#lin{
margin-left: 2%;
font-size: 18px;
}
.butt{
font-size: 18px;
}

</style>
</head>
<body>

<div class="caixa" >
<form action="" accept-charset="utf-8">
<fieldset>
	<legend>Formulario de inscrição</legend>
<p>
<label>Nome:</label>
<input type="text" name="Nome" id="nome" placeholder="insira seu nome ">
</p>

<p>
<label>Sobrenome:</label>
<input type="text" name="Nome" id="Sobrenome" placeholder="insira seu Sobrenome ">
</p>

<p>
<label>idade:</label>
<input type="number" name="idade" id="idade">
</p>

<p>
<label>Email:</label>
<input type="text" name="Email" id="email" placeholder="insira seu email ">
</p>

<p>
<label>Sexo:</label>
<input type="radio" name="Sexo" value="1" id="masculino" class="TRE"> Masculino
<input type="radio" name="Sexo" value="1" id="feminino" > Feminino
<input type="radio" name="Sexo" value="1" id="outro" > Outro
</p>

<p>
<label>Foto:</label>
<input type="file" name="Chosem File" value="Chosem File"  id="foto">
</p>

<p>
<label>País:</label>	
<select id="País" >
	<option value="1">Argentina</option>
	<option value="2">Brasil</option>
	<option value="3">Uruguai</option>
	<option value="4">Paraquai</option>
</select>
</p>

<p>
<label>As linguagens que você prefere?</label>
<select name="" multiple id="lin">
	<option value="1">java</option>
	<option value="1">c++</option>
	<option value="1">python</option>
	<option value="1">PHP</option>
</select>(Para fazer várias escolhas, matenha a tecla CTRL pressionada)	
</p>

<p>
<label>Aréas de atuação:</label>
<input type="checkbox" name="Computação" value="1" class="are">Computação
<input type="checkbox" name="Gestão" value="2">Gestão
<input type="checkbox" name="Pedagogia" value="3">Pedagogia
</p>

<p>
<input type="button"  value="Enviar" class="butt">
<input type="reset" name="" value="Limpar" class="butt">
</p>

</fieldset>



	

</form>
</div>
</body>

</html>
© 2021 GitHub, Inc.

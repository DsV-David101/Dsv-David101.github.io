<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dsv_calc.github.io</title>
</head>

<body>
  <h1>DsV-calc</h1>
  <form name="all">
    <input name="answer" placeholder="0">
    <br>
    <br>
    <div id="tudo">
      <div id="botão">
        <br> <input value="1" type="button" onclick="all.answer.value+='1'">
        <input value="2" type="button" onclick="all.answer.value+='2'">
        <input value="3" type="button" onclick="all.answer.value+='3'">
      </div>
      <br>
      <div>
        <input value="4" type="button" onclick="all.answer.value+='4'">
        <input value="5" type="button" onclick="all.answer.value+='5'">
        <input value="6" type="button" onclick="all.answer.value+='6'">
      </div>
      <br>
      <div>
        <input value="7" type="button" onclick="all.answer.value+='7'">
        <input value="8" type="button" onclick="all.answer.value+='8'">
        <input value="9" type="button" onclick="all.answer.value+='9'">
      </div>
      <br>
      <div>
        <input value="0" type="button" onclick="all.answer.value+='0'">
        <input id="adição" value="+" type="button" onclick="all.answer.value+='+'">
        <input id="diferença" value="-" type="button" onclick="all.answer.value+='-'">
      </div>
      <br>
      <div>
        <input id="multiplicar" value="×" type="button" onclick="all.answer.value+='*'">
        <input id="dividir" value="÷" type="button" onclick="all.answer.value+='/'">
        <input id="igual" value="=" type="button" onclick="all.answer.value=eval(all.answer.value)">
        <br>
        <br>
        <input id="apagar" type="button" value="apagar" onclick="all.answer.value=' '">
      </div>
    </div>
    <div>
    </div>
    <footer>
      DsV-HcK101
    </footer>
    <br>
    <br>
    <br>
  </form>
  <script>


</script>
  <style>
/*parte de tudo*/
body {
    font-size:20pt;
    background-color:black;
    text-align:center;
    right:12;
    
    
}
/*parte do botão*/
 div input{
  color:white;
  background-color:black;
  font-size:52px;
  border-radius:10px;
  border-color:white;
  
  
  
}
/*parte que mostra o resultado*/
input[name="answer"]{
  color:green;
  background:black;
  font-family:VT323;
  font-size:27px;
  
}/*parte do cabeção */
header{
  text-align:right;
color:white;
}
footer{
  text-align:right;
  color:white;
}
input[id="igual"]{
  color:green;
  background-color:black;
}
input[id="adição"]{
  color:green;
  background-color:black;
}
input[id="multiplicar"]{
  color:green;
  background-color:black;
}
input[id="dividir"]{
  color:green;
  background-color:black;
}
input[id="diferença"]{
  color:green;
  background-color:black;
}
input[id="apagar"]{
  color:green ;
  background-color:black;
  font-size:30px;
  text-align:right;
}
div[id="tudo"]{
  background-color:black;
  border-radius:10px;
  background-size:12px;
  border-radius:20px;
}
input[name="answer"]{
  color:white;
  background-color:black;
  font-size:30px;
  
}
input[type="button"]{
  font-size:39px;
  border-radius:5px;
  color:green;
}

</style>
</body>

</html>

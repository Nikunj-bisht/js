# js
<html>

<style>
 .turn{

  font-size:40px;
  padding:40px;
  text-align:center;
  margin:40px;
  border:5px solid:blue;
}
input[type=textbox]{
  height:60px;
  font-size:40px;
  border-width:5px;
  border-color:black;
  padding:20px;
  margin:20px;
  background-color: grey;


}
input[type=button]{
  font-size:40px;
  padding:20px;
  background-color:tomato;
   color:white;
   opacity:0.6;
   transition:0.4s;
  font-style:bold;
  border-radius:18px;
  cursor:pointer;

}
input:hover[type=button]{

  opacity:1;
}
body{
  background-color:
}
</style>

<script>

function display(n)
{
  out.text.value+=n;
}
function back(){
  out.text.value="";

}


</script>
<body>

  <div class="turn">
    <form name="out">
  <input type="textbox" name="text"><br>
<input type="button" value="0" name="btn0" onclick="display(btn0.value)">
<input type="button" value="1" name="btn1" onclick="display(btn1.value)">
<input type="button" value="2" name="btn2" onclick="display(btn2.value)">
<input type="button" value="3" name="btn3" onclick="display(btn3.value)"><br>
<input type="button" value="4" name="btn4" onclick="display(btn4.value)">
<input type="button" value="5" name="btn5" onclick="display(btn5.value)">
<input type="button" value="6" name="btn6" onclick="display(btn6.value)">
<input type="button" value="7" name="btn7" onclick="display(btn7.value)"><br>
<input type="button" value="8" name="btn8" onclick="display(btn8.value)">
<input type="button" value="9" name="btn9" onclick="display(btn9.value)">
<input type="button" value="+" name="add" onclick="display(add.value)">
<input type="button" value="-" name="minus" onclick="display(minus.value)"><br>
<input type="button" value="*" name="mult" onclick="display(mult.value)">
<input type="button" value="/" name="divd" onclick="display(divd.value)">
<input type="button" value="=" name="result" onclick="out.text.value=eval(out.text.value)">
<input type="button" value="clr" name="clear" onclick="back()">
</div>
</body>

</html>

# 2018-4-24
if语句
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>W3Cschool教程(w3cschool.cn)</title>
</head>
<body>

<p>如果时间早于20：00，会获得问候“Good day”。</p>
<button onclick="myFunction()">点击这里</button>
<p id="demo"></p>
<script>
function myFunction(){
  var x="";
  var time=new Date().getHours();
  if (time<20){
    x="Good day";
    }
  document.getElementById("demo").innerHTML=x;
}
</script>

</body>
</html>

If...else 语句
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>W3Cschool教程(w3cschool.cn)</title>
</head>
<body>

<p>点击这个按钮，获得基于时间的问候。</p>
<button onclick="myFunction()">点击这里</button>
<p id="demo"></p>
<script>
function myFunction()
{
  var x="";
  var time=new Date().getHours();
  if (time<20)
  {
    x="Good day";
  }
  else
  {
    x="Good evening";
  }
  document.getElementById("demo").innerHTML=x;
}
</script>

</body>
</html>

# ditcstest<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <style>
           body{
            background-color: lightgreen;
            text-align:center;

          }
          h2{
            color: blue;
          }

          button{
            background-color: pink;
            width: 50px;
            height: 50px;
          }
          input{
            width: 200px;
            height: 30px;
          }
          p{
            color: blue;
          }

        </style>

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
   <script>
   $(document).ready(function(){
     $("#btn1").click(function(){
       $("#test1").val("50,000");
     });
   });

   $(document).ready(function(){
     $("#btn2").click(function(){
       $("#test2").val("");
     });
   });
   $(document).ready(function(){
     $("#btn4").click(function(){
       $("#test2").val("0");
     });
   });
   $(document).ready(function(){
     $("#btn5").click(function(){
       $("#test2").val("1");
     });
   });
   $(document).ready(function(){
     $("#btn6").click(function(){
       $("#test2").val("2");
     });
   });
   $(document).ready(function(){
     $("#btn7").click(function(){
       $("#test2").val("3");
     });
   });
   $(document).ready(function(){
     $("#btn8").click(function(){
       $("#test2").val("4");
     });
   });
   $(document).ready(function(){
     $("#btn9").click(function(){
       $("#test2").val("5");
     });
   });
   $(document).ready(function(){
     $("#btn10").click(function(){
       $("#test2").val("6");
     });
   });
   $(document).ready(function(){
     $("#btn11").click(function(){
       $("#test2").val("7");
     });
   });
   $(document).ready(function(){
     $("#btn12").click(function(){
       $("#test2").val("8");
     });
   });
   $(document).ready(function(){
     $("#btn13").click(function(){
       $("#test2").val("9");
     });
   });
  </script>
</head>
<body>

<h2>마일리지 관리 프로그램</h2>
<p>금액: <input type="text" id="test1" value="금액을 입력하세요">
<button id="btn1">입력</button></p>

<p>전화번호: <input type="text" id="test2" value="전화번호를 입력하세요">
<button onclick="alert('저장 완료')">저장</button>
<button id="btn2">c</button>
<button id="btn3">x</button></p>
<button id="btn4">0</button>
<button id="btn5">1</button>
<button id="btn6">2</button>
<button id="btn7">3</button>
<button id="btn8">4</button>
<button id="btn9">5</button>
<button id="btn10">6</button>
<button id="btn11">7</button>
<button id="btn12">8</button>
<button id="btn13">9</button>
</body>
</html>

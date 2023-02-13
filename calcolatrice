<html>
  <head>
    <title>Calcolatrice</title>
  </head>
  <body>
    <h1>Calcolatrice</h1>
    <input type="text" id="display">
    <br><br>
    <button id="1">1</button>
    <button id="2">2</button>
    <button id="3">3</button>
    <button id="plus">+</button><br>
    <button id="4">4</button>
    <button id="5">5</button>
    <button id="6">6</button>
    <button id="minus">-</button><br>
    <button id="7">7</button>
    <button id="8">8</button>
    <button id="9">9</button>
    <button id="times">*</button><br>
    <button id="clear">C</button>
    <button id="0">0</button>
    <button id="equals">=</button>
    <button id="divide">/</button><br>
    <script>
      const display = document.getElementById("display");
      const btns = document.querySelectorAll("button");
      btns.forEach(function(btn){
        btn.addEventListener("click", function(){
          let value = btn.innerHTML;
          if(value === "C"){
            display.value = "";
          } else if(value === "="){
            display.value = eval(display.value);
          } else {
            display.value += value;
          }
        });
      });
    </script>
  </body>
</html>

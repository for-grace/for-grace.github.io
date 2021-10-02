<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8"/>
    <title>For Grace :D</title>
  </head>
  <body>
    <h1 id="changingtext">Happy birthday Grace!</h1>
    <script>
      const changedtext = document.getElementById("changingtext");
      var clicked = 0
      document.body.onkeyup = function(e){
        if(e.keyCode == 32){
          clicked ++
          switch(clicked) {
            case 0:
              changedtext.textContent = "Happy birthday Grace!"
              break;
            case 1:
              changedtext.textContent = "*Sentimental message 1 here*"
              break;
            case 2:
              changedtext.textContent = "*Sentimental message 2 here*"
              break;
            case 3:
              changedtext.textContent = "*Sentimental message 3 here*"
              break;
            case 4:
              changedtext.textContent = "*big funny joke here*"
              break;
            case 5:
              changedtext.textContent = "K bye"
              break;
            case 6:
              changedtext.textContent = "Directed by Dominick Green"
              break;
            case 7:
              changedtext.textContent = "Holly did nothing but is still super happy"
              break;
          }
        }
      }
    </script>
  </body>
</html>

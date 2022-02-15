### START

### INIT(Brew French Press Coffee)

<hr>
function brewCoffee() {<br>

var grounds = "2T ground coffee";<br>
var container = (coffee, water); <br>
var water = "12oz boiling water";<br>

function coffeeType(type) {<br>
  let type = ("light", "medium", "dark");<br>
}
<hr>

### INPUT ground coffee to the french press
 * addGrounds

WHILE container is empty add grounds<br>
ENDWHILE

<hr>
function addGrounds() {<br>
    while (container = empty) {<br>
    return "add grounds";<br>
    }<br>
}
<hr>

### INPUT water to the container
  * addWater
  
  WHILE boiling water amount is less than amount needed<br>
   add water<br>
  ENDWHILE
  
  <hr>
  while (boiledWater < 12) {<br>
   return "add water";<br>
   }
  <hr>
  
### COMPUTE brew time based on the type of coffee (light, medium, dark)
 * brewTime
 * coffeeType
   * dark roast = 2 min
   * medium roast = 4 min
   * light roast = 6 min

 FOR coffee type used<br>
  IF type is light brew for 6 minutes;<br>
   ELSEIF type is medium brew for 4 minutes;<br>
   ELSE brew for 2 minutes;<br>
  ENDIF<br>
 ENDFOR

<hr>
brewTime(type, time) {<br>
  const time = 120;<br>
  
  for (type of coffeeType(type)) {<br>
    if (type["0"]) {<br>
      return "type" + time * 3;<br>
      } else if (type["1"]) {<br>
      return "type" + time * 2;<br>
      } else {<br>
      return "type" + time;<br>
      }
<hr>

### Add lid and depress filter for 30 secs;
* filterCoffee
  * lidOn
  * depressLid

 IF lid is not on add lid <br>
 ELSE if lid is on depress for 30 seconds <br>
 ENDIF
 
 <hr>
 function filterCoffee() {<br>
 
 const lidOn = true;<br>
 const depressTime = 30;<br>
  function depressLid() {<br>
  return depressTime;<br>
  }<br>
  if (lidOn !== true) {<br>
  return "add lid";<br>
  } else {<br>
  depressLid();<br>
  }<br>
 }
 <hr>
 
### WHILE mug is empty keep filling it;
* mugEmpty

IF mug is empty<br>
THEN fill the mug<br>
ENDIF

<hr>
if (mugEmpty = true) {<br>
 return "pour coffee";<br>
 }
<hr>

### END the program
<hr>
}<br>

brewCoffee();

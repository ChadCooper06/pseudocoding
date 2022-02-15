### START

### INIT(French Press Coffee)

<hr>
function brewCoffee() {

var grounds = "2T ground coffee";
var container = (coffee, water); 
var water = "12oz boiling water";

function coffeeType(type) {
  let type = ("light", "medium", "dark");
}
<hr>

### INPUT ground coffee to the french press
 * addGrounds

WHILE container is empty add grounds
ENDWHILE

<hr>
function addGrounds() {
    while (container = empty) {
    return "add grounds";
    }
}
<hr>

### INPUT water to the container
  * addWater
  
  WHILE boiling water amount is less than amount needed
   add water
  ENDWHILE
  
  <hr>
  while (boiledWater < 12) {
   return "add water";
   }
  <hr>
  
### COMPUTE brew time based on the type of coffee (light, medium, dark)
 * brewTime
 * coffeeType
   * dark roast = 2 min
   * medium roast = 4 min
   * light roast = 6 min

 FOR coffee type used
  IF type is light brew for 6 minutes;
   ELSEIF type is medium brew for 4 minutes;
   ELSE brew for 2 minutes;
  ENDIF
 ENDFOR

<hr>
brewTime(type, time) {
  const time = 120;
  
  for (type of coffeeType(type)) {
    if (type["0"]) {
      return "type" + time * 3;
      } else if (type["1"]) {
      return "type" + time * 2;
      } else {
      return "type" + time:
      }
<hr>

### Add lid and depress filter for 30 secs;
* filterCoffee
  * lidOn
  * depressLid

 IF lid is not on add lid
 ELSE if lid is on depress for 30 seconds
 ENDIF
 
 <hr>
 function filterCoffee() {
 
 const lidOn = true;
 const depressTime = 30;
  function depressLid() {
  return depressTime;
  }
  if (lidOn !== true) {
  return "add lid";
  } else {
  depressLid();
  }
 }
 <hr>
 
### WHILE mug is empty keep filling it;
* mugEmpty

IF mug is empty
THEN fill the mug
ENDIF

<hr>
if (mugEmpty = true) {
 return "pour coffee";
 }
<hr>

### END the program
<hr>
}

brewCoffee();

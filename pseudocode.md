START

## French Press Coffee

// function brewCoffee() {
//
//var grounds = 2T;
//var container = (coffee, water);

INPUT coffee

### User measures out 2 tbsp coffee grounds and places into the container
  * measure out 2T coffee grounds
  * place them into the container
     * is it empty?-if yes add them, if no then add water


  \* if (container = empty) {
    return "add grounds";
    } else {
    return "add water"
    }

function coffeeType(type) {
  let type = ("light", "medium", "dark")
} *\

INPUT water
### User adds 12 oz boiling water to the container
  * is there water? if yes go to brew, if no then add it
  
  FOR water less than 12 oz
    IF water is less than 12 oz add water
    ELSE brew
    
  for (i=0, i<12, i++) {
    if (i
    
  ENDFOR
  
COMPUTE brew time
### User determines how long to brew based on the type of grounds (light, medium, dark)
  * dark roast = 2 min
  * medium roast = 4 min
  * light roast = 6 min

INCREMENT time based on type-dark to light

  FOR coffee type used
    CASE type
      light: 6 min
      medium: 4 min
      dark: 2 min
      ENDCASE
  ENDFOR
  
/* brewTime(type, time) {
  const time = 120;
  
  for (type of coffeeType(type)) {
    if (type["1"]) {
      return time * 2;
      } else if (type["0"]) {
      return time * 3;
      } else {
      return time:
      } */
      

### Add lid and depress filter

### Pour into a mug

### Drink the coffee

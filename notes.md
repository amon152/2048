# Structuur

index.html \
styles.css \
index.js \
/js/Game.js \
/js/Board.js \
/js/Tile.js \
/js/Handler.js


## Index.js
is waar de game start. Verzamel hier in de klassen en keyHandler.
```javascript
window.onload = () => {}
```

## Game.js
Heeft logika over de game zelf. \
**Variabelen:**
```javascript
this.size = 4 
```

**Functies:**
```javascript
startGame()  
drawUpdate() 
```
## Board.js *extends Game*
Bevat alle functies met betrekking tot het bord.
```javascript
grid() 
getBoard() 
```

## Tile.js *extends Board*
Bevat alle functies voor tegels\
**Variabelen:**
```javascript
this.tileValue = 2 
```
**Functies:**
```javascript
isValid(x,y) 
random()
get()
set(x,y)
clear(x,y)
hasEmpty(row, col, toCheckRow, toCheckCol) 
hasSameValue(row, col, toCheckRow, toCheckCol) 
```









# Chess.js
A simple Javascript chess library that makes it easy to implement a fully playable chessboard on any html website.

## Usage
The code below shows you how you can implement a chessboard in HTML. 
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <script src="Chess.js"></script>
    </head>
    <body>
        <canvas id="chessCanvas" width="500" height="500"></canvas>
        <script>
            var chessBoard = new ChessBoard(document.getElementById("chessCanvas"));
        </script>
    </body>
</html>
```
#### Moving pieces
There is functionality for moving pieces with the mouse. The code below shows you how you can do it programmatically.
```javascript

let from = {x:0,y:0};
let to = {x:0,y:5};

chessBoard.board.MakeMove(from,to);

```
The move will be made if the move is a valid chess move. The upper left cell is x: 0, y: 0. 

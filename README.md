# Chess.js
A simple Javascript chess library that makes it easy to implement a fully playable chessboard on any html website.

## Usage
The code below shows you how you can implement the chessboard. 
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

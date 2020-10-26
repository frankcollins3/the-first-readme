
```javascript
const handleWin = (letter) => {
    gameIsLive = false;
    if (letter === "x") {
        statusDiv.innerHTML = '${letterToSymbol(letter)} has won!';
    } else {
        statusDiv.innerHTML = '<span>${letterToSymbol(letter)} has won! </span>'
    }
    };
    ```

// I don't know why ```css is graying out the layout below. 
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}
```
| Syntax | Description |
| ----------- | ----------- |
| Header | Title | 
| Paragraph | Text |

| Functions             | Description  |
| ------------ | ----------- |
| `handleWin()` | Handle the win of either player |
| `checkGameStatus()` | Check the status after each turn 


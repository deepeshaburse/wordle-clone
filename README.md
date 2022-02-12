# wordle-clone
const dataLetter = tile.getAttribute("data");
tile.classList.add("flip");
            if(dataLetter === wordle[index]) {
                tile.classList.add("green-overlay");
                addColorToKey(dataLetter, "green-overlay");
            }
    
            else if(wordle.includes(dataLetter)) {
                tile.classList.add("yellow-overlay");
                addColorToKey(dataLetter, "yellow-overlay");
            }
    
            else {
                tile.classList.add("gray-overlay");
                addColorToKey(dataLetter, "gray-overlay");
            }
In this project, I will create a Rock, Paper, Scissors game using what I've learned in the first portion of web development from The Odin Project.

** 03/31/20 Update **

Before when I created the rock paper scissors game it was only available to play via input, and results were displayed in the developer tools. I didn't have any knowledge of loops as well so I am going to edit the function game() to run using loops instead of repeating the console.log method 5x. 

I will also be adding a simple UI to the game using what I've learned about DOM manipulation from The Odin Project. 

** 04/02/20 Update **

I ran several problems on adding a UI using only Dom Manipulation on this project. First and foremost, I found it relatively easy to create buttons, I created a 'create button' function that would create a button for the thre RPS option. The part I struggled with greatly in this project is to 'print' and or keep score of my score, and the pc score dynamically as I was pressing the buttons.

I ended up figuring it out by inserting directly into the HTMl via .innerHTML the score, and was able to edit that variable dynamically by grabbing the object ${}. I then added several appendages onto the document such as headers, and paragraphs where I would print these results and had my game() function which was called on each button press to check if any of the score's were 5, if not, it would run the game again and increment the score of the winner and so on until one of us reached 5. Tough work for me for now but I got through it! 

# Psychic-Game

## What was I supposed to be doing?
For this assignment I was building a game in which a player tries to guess a letter randomly generated by the browser within ten tries.

## Technologies used:
* HTML
* JavaScript
* CSS

## What I did:
After building the basic structure of the game in HTML, the first thing I did in JavaScript was defining variables which included an array of all letters, counters for: wins, losses, guesses remaining, and the letters the players had guesses, alongside values that linked those values back to the basic HTML of the page. I then built a random number generator to pick a latter and set the browser to be detecting key presses. Then I made the logic stating that if the player's guess was the same as the computer's guess wins would be increased, and if it didn't the guesses they had left would be decreased. If the guesses they had hit zero, the player's losses would be increased. Lastly in JavaScript, I added a message that tells the player what the computer picked and resets the guesses they have after the game ends. Then I added in CSS and the theme I decided to use was an old fortune teller booth because that's what I arbitrarily felt like doing.

## Problems I Encountered
I couldn't get autoplay on an MP3 to work and I spent an embarrassing amount of time searching for a complex error when the mistake I made was simply using a comparator to reset the guesses.

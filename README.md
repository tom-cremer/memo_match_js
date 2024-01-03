# Memo Match Game

*!! 
Quick disclaimer: 
The following exercise have been produced by Chat-GPT3.5, it's the simple description of the steps to achieve this exercise 
!!*

Build a classic memory matching game where users need to match pairs of cards.
You can create a grid of cards that flip when clicked, and users should try to find all matching pairs. 
Use HTML for the game layout, CSS for styling, and JavaScript for handling game logic, card flipping, and scoring.


### 1. Set Up HTML Structure:
- Create a container element for the game grid.
- Inside the container, add a grid of cards (div elements) using nested loops or a predefined structure.
- Each card should initially have a hidden face and be clickable.

### 2. Style the Cards:
- Use CSS to style the cards, making them visually appealing.
- Add CSS rules to hide the back of the cards initially and style the front face.
- Apply styles for card flipping animations or transitions.

### 3. Add Click Event Listeners:
- Use JavaScript to select all the cards and add click event listeners to each card.
- When a card is clicked, trigger a function to handle the card flipping logic.

### 4. Card Flipping Logic:
- In the click event handler, check if the clicked card is already flipped or if two cards are already flipped.
- If not, flip the card to reveal its face.
- If it's the first card flipped, store its information (e.g., value, position).
- If it's the second card flipped, compare it with the first card.
- If they match, leave them face up; otherwise, flip them back face down after a short delay.

### 5. Game Logic:
- Keep track of the number of moves and the number of matched pairs.
- Implement logic to end the game when all pairs are matched.
- Display a congratulatory message or score when the game is completed.

### 6. Restart Button:
- Add a restart button that resets the game by shuffling the cards and resetting the game state.

### 7. Timer and Score (Optional):
- Optionally, add a timer to track how long it takes to complete the game.
- Implement a scoring system based on the number of moves or time taken.

### 8. Responsive Design:
- Ensure that your game is responsive by using CSS media queries or flexible layouts.
- Test the game on different screen sizes to ensure a good user experience.

### 9. Testing and Debugging:
- Test your game thoroughly to identify and fix any bugs.
- Use browser developer tools for debugging.


Have fun with JavaScript 😉
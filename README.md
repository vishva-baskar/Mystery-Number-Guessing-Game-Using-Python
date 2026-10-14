# My Python Learning Journey: Mystery Number Guessing Game 🎮

Welcome to my repository! This project documents my step-by-step journey learning Python. I built a complete "Mystery Number Guessing Game" by starting with the absolute basics and gradually adding advanced programming concepts—one phase at a time.

## 🚀 Learning Roadmap

* **Phase 1**: Starting simple with basic variables and `if-else` conditions[cite: 1].
* **Phase 2**: Learning how to repeat actions using `for` and `while` loops[cite: 2].
* **Phase 3**: Adding game rules, number validation, and tracking attempts[cite: 3].
* **Phase 4**: Making the game exciting by adding random numbers and flexible loops[cite: 4].
* **Phase 5**: Writing robust code using error handling (`try-except`)[cite: 5].
* **Phase 6**: Organizing my code into reusable functions[cite: 6].

---

## 📚 Phase-by-Phase Learning Descriptions

### Phase 1: Simple Logic & Conditions
* **What I learned**: How to take input from a user, store data in a variable, and make decisions using basic conditional statements (`if-else`)[cite: 1].
* **How it works**: I started with a fixed secret number (`74`), asked the user to guess it once, and checked if they got it right or wrong[cite: 1].

### Phase 2: Introducing Loops (Repetition)
* **What I learned**: How to avoid writing repetitive code by using loops when tasks need to run multiple times[cite: 2].
* **How it works**: 
  * **`for` loop (2.1)**: Used when I know the exact number of turns allowed (e.g., 7 attempts)[cite: 2].
  * **`while` loop (2.2)**: Used to keep the game running infinitely until the correct answer is found[cite: 2].

### Phase 3: Game Rules & Attempt Tracking
* **What I learned**: How to handle multiple conditions, validate user boundaries, and keep track of score or attempts[cite: 3].
* **How it works**: I added rules to check if the input is between $1$ and $100$, gave hints if the guess was too high or too low, and capped the game at a maximum of $7$ attempts[cite: 3].

### Phase 4: Randomization & Dynamic Loops
* **What I learned**: How to import Python libraries (`random`) and manage loop counters dynamically[cite: 4].
* **How it works**: 
  * **Random Library (4.1)**: Used `random.randint(1,100)` so the secret number changes automatically every time I play[cite: 4].
  * **Dynamic Attempts (4.2)**: Switched to a `while` loop that counts my attempts on the fly until I win[cite: 4].

### Phase 5: Exception Handling (Crash Prevention)
* **What I learned**: How to prevent my program from crashing when a user types unexpected things (like letters instead of numbers)[cite: 5].
* **How it works**: I wrapped my input code inside a `try-except` block to catch `ValueError` errors, allowing the game to politely warn the player and let them try again[cite: 5].

### Phase 6: Functions & Clean Code
* **What I learned**: How to package code into reusable blocks called functions so I can run the game whenever I want with a single command[cite: 6].
* **How it works**: I wrapped all my game logic into a clean function named `mystery_number_gussing_game()`[cite: 6].

---

## 💻 How to Run
1. Open any phase notebook or script.
2. Call the function or run the cells:
   ```python
   mystery_number_gussing_game()
   

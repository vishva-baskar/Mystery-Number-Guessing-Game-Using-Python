# Mystery Number Guessing Game 🎮(Using Python)

A progressive Python project that builds a complete, robust "Mystery Number Guessing Game" from scratch. This repository demonstrates how a simple script evolves through iterative programming concepts—from basic variables and conditional logic to loops, random module integration, error handling, and modular functions.

## Project Evolution Overview

* **Phase 1**: Basic setup with fixed variables and conditional statements.
* **Phase 2**: Adding repetition using `for` and `while` loops.
* **Phase 3**: Implementing multi-condition rules, validation, and attempt limitations.
* **Phase 4**: Introducing randomization with the `python random` library.
* **Phase 5**: Adding exception handling (`try-except`) for invalid character inputs.
* **Phase 6**: Encapsulating the complete logic inside a reusable Python function.

---

## Phase Descriptions

### Phase 1: Simple Logic & Conditions
* **Goal**: Introduction to basic input/output and checking static values[cite: 1].
* **Description**: Uses a hardcoded `secret_number` (`74`) and collects a single input from the user[cite: 1]. It compares the user's guess against the secret number using basic `if-else` statements to check if the guess is correct[cite: 1].

### Phase 2: Introducing Loops
* **Goal**: Allow multiple interaction turns without restarting the program[cite: 2].
* **Description**: 
  * **`for` loop (2.1)**: Runs a fixed sequence (7 iterations) using `range(7)` so the user can make multiple attempts[cite: 2].
  * **`while` loop (2.2)**: Runs an indefinite loop (`while True`) that continuously prompts the user until they correctly guess the static secret number[cite: 2].

### Phase 3: Game Rules & Attempt Tracking
* **Goal**: Add boundary checks, comparative hints, and a strict attempt cap[cite: 3].
* **Description**: Enhances the game flow by ensuring numbers are within a $1-100$ range, giving hints whether a guess is higher or lower than the secret number, and restricting gameplay to a maximum of $7$ attempts before ending the game[cite: 3].

### Phase 4: Randomization & Flexible Loops
* **Goal**: Make the game dynamic and unpredictable[cite: 4].
* **Description**: 
  * **Random Library (4.1)**: Uses `random.randint(1,100)` to generate a different secret number every time the game runs while keeping the $7$-attempt limit[cite: 4].
  * **Dynamic Attempts (4.2)**: Replaces the `for` loop with a `while True` loop that increments an `attempts` counter dynamically until the user wins[cite: 4].

### Phase 5: Exception Handling
* **Goal**: Prevent program crashes caused by invalid text inputs[cite: 5].
* **Description**: Wraps the input collection inside a `try-except` block to catch `ValueError` exceptions[cite: 5]. If a user types letters or symbols instead of a number, the program gracefully prints a warning message and lets them try again without crashing[cite: 5].

### Phase 6: Functions & Reusability
* **Goal**: Wrap the complete game code into a clean, callable function[cite: 6].
* **Description**: Encapsulates the entire game logic (randomization, loop controls, hint checks, exception handling) inside a function named `mystery_number_gussing_game()`, making it easy to invoke and replay anytime[cite: 6].

---

## How to Run
1. Ensure you have Python installed.
2. Run any of the phase scripts or load the final function from Phase 6 in your terminal or Jupyter Notebook:
   ```python
   mystery_number_gussing_game()

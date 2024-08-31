# Bagels

Bagels is a deductive logic game where you must guess a 3-digit number based on clues provided after each guess. The game was created by Mohammed Al-Mokhtar.

## How to Play

In this game, the computer thinks of a random 3-digit number with no repeated digits, and you have up to 10 guesses to figure out what it is. After each guess, you'll receive clues to help you get closer to the correct number:

- **Pico:** One digit is correct but in the wrong position.
- **Fermi:** One digit is correct and in the right position.
- **Bagels:** No digit is correct.

For example, if the secret number was 248 and your guess was 843, the clues would be "Fermi Pico" (one digit is correct and in the right position, and another digit is correct but in the wrong position).

## Running the Game

To play Bagels, you can run the Python script directly:

```bash
python bagels.py

User Manual for Tunisian Card Game Simulator
Introduction:
Welcome to the Tunisian Card Game Simulator! This Python program allows you to simulate and analyze the outcomes of various Tunisian card games using Monte Carlo simulations. The simulator includes pre-defined games like Sahara Ace, Tunisian Twins, Medina Biggie, Desert Hearts, Oasis Runny, and a custom game called StudentGame.
Usage Instructions:
Prerequisites:
Make sure you have Python installed on your system. You can download it from python.org.
Save the provided code in a Python file, for example,TP1simulation.py.
Run the Simulator:
Open a terminal or command prompt.
Navigate to the directory containing the Python file (TP1simulation.py).
Run the script by executing the command: python TP1simulation.py.
or you can use VScode it is practical and better.
Simulator Output:
The simulator will run Monte Carlo simulations for each of the pre-defined games.
You will see the probability of winning and the expected winnings per play for each game after 100,000 simulations.
Understanding the Results:
Probability of Winning: This value represents the likelihood of winning the game based on the Monte Carlo simulations.
Expected Winnings per Play: This value indicates the average winnings a player can expect per play after multiple simulations.
Custom Game - StudentGame:
The StudentGame class represents a custom game where the player wins 40 dinars if they draw 4 cards, and at least one of them is a diamond, with an even number of diamonds.
Important Note:
The simulations are based on randomness, and results may vary with each run.
The provided code includes a seed (random.seed(619)) for reproducibility.(When we change the seed the results will change for sure).
Example Output:
Sahara Ace - Probability of Winning: 0.7642, Expected Winnings per Play: 0.7642
Tunisian Twins - Probability of Winning: 0.0, Expected Winnings per Play: 0.0
Medina Biggie - Probability of Winning: 0.9433, Expected Winnings per Play: 0.9433
Desert Hearts - Probability of Winning: 0.74718, Expected Winnings per Play: 0.74718
Oasis Runny - Probability of Winning: 1.0385, Expected Winnings per Play: 1.0385
StudentGame - Probability of Winning: 8.6312, Expected Winnings per Play: 8.6312

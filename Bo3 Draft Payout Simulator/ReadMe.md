Austin Herrick

# mtga_bo3_draft_simulator.py

This script uses simulators to determine the average payouts at various winrates of Magic Arena's (MTGA) Traditional Best of 3 Drafts. In particular, I am examining the impact of the changes in prize support described in the development blog here:
https://magic.wizards.com/en/articles/archive/magic-digital/mtg-arena-state-game-april-2020-04-13

The below classes allow users to run their own simulations, and the `generate_prize_distributions` function automates the work needed to create the data used as an input to the provided charts.

# LargeSimResults.csv

This csv contains the results of a simulation of 1% increment winrates, with 500,000 drafts per winrate per payout scheme. Noise is very low, and this data was use for the attached charts.
This code is based on Whidden's original Pokemon Red AI project.

It requires both PyBoy and a Pokemon Red game on the hosting PC.

For full directions on the project see, https://github.com/PWhiddy/PokemonRedExperiments

This GitHub hosts the files modified under the baseline folder of Whidden's experiment.

The modified features include: a combat reward for large, super-effective and critical hits, a death penalty (modified from original), a healing reward (modified from the original), a KO reward,
  a penalty for jittery movement with no progress, a reward for walking a distance without turning (tiers), a reward for free items (but not for bought items), rewards for traveling to specified maps
  with a time limit (tiers), a reward for adding more pokemon to the party, a badge reward (not tested in run), and hm reward (not tested in run), a penalty for staying too long in a menu and spamming 
  buttons.

This is added to Whidden's original code and project.

There may still be errors and bugs. The jitter penalty could be more sensitive. The combat reward could be weakened. A penalty for staying too long on one map could be added.

The file with most of the edits is the red_gym.env. Using run_baseline_parallel.py and run_pretrained_interactive.py. This version only can go the the far side of Mt Moon, but that's such a major obstacle
  for game playing agents that it's enough. 

Since GitHub won't let me upload a video or a .txt file???? Here is a link to the demo (quite rough) on Drive: https://drive.google.com/file/d/12bV_bzAoEmgJ_5cS5ICqPTPOxgqAqxsW/view?usp=drive_link

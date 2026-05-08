This code is based on Whidden's original Pokemon Red AI project.

It requires both PyBoy and a Pokemon Red game on the hosting PC.

For full directions on the project see, https://github.com/PWhiddy/PokemonRedExperiments

This GitHub hosts the files modified under the baseline folder of Whidden's experiment.

The modified features include: a combat reward for large, super-effective and critical hits and KOs, a death penalty (modified from original), a healing reward (modified from the original),
  a penalty for jittery movement with no progress, a reward for walking a distance without turning (tiers), a reward for free items (but not for bought items), rewards for traveling to specified maps
  with a time limit (tiers), a reward for adding more pokemon to the party, a badge reward (not tested in run), and hm reward (not tested in run), a penalty for staying too long in a menu and spamming 
  buttons and a penalty for staying on the same map too long.

This is added to Whidden's original code and project.

There may still be errors and bugs. The jitter penalty has been adjusted. The combat reward has been weakened. The reward for traveling in the same direction has been improved. The exploration reward 
  has been strengthened. The healing reward has been tiered and weakened and a check for healing by fainting was added.

The file with most of the edits is the red_gym.env. Using run_baseline_parallel.py and run_pretrained_interactive.py. This version only can go the the far side of Mt Moon, but that's such a major obstacle
  for game playing agents that it's enough. The session data in run_pretrained_interactive.py must be updated to the coreect zip before running.

Here is a link to the demo (quite rough) on Drive: https://drive.google.com/file/d/12bV_bzAoEmgJ_5cS5ICqPTPOxgqAqxsW/view?usp=drive_link. I smaller video of the current version has also been added. Note: it is based on an earlier trainin run (5-7-26)

As of 5-8-26, the AI agent can make it to Viridian City. It is still in training. It may be manipulating an item glitch in the menu, not confirmed.

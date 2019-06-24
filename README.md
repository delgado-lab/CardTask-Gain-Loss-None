# Description of Task Files for “CardTaskRPN”

## Used in publications:
Task is very similar (differences in trial numbers) to the one used in: <br>
May, J. C., Delgado, M. R., Dahl, R. E., Stenger, V. A., Ryan, N. D., Fiez, J. A., & Carter, C. S. (2004). <br>
Event-related functional magnetic resonance imaging of reward-related brain circuitry in children and adolescents. <br>
Biological psychiatry, 55(4), 359-366.<br>

## Important Filenames:
*CardTaskRPN.es2* - e-prime main file<br>
*{}.png* - images needed for the e-prime presentation<br>

## File Descriptions
### CardTaskRPN.es2:
*Experimental Design:* 3 conditions (Reward, Punishment, No Outcome) within subjects <br>

*Timing Information:*<br>
Structured for one 9min 20s scan (does not include practice trials)<br>
Event Timing (each trial) -  
  1.	Input guess: 2s
  2.	Outcome: 1s, Reward/Punishment/Neutral (24/24/16 trials), or “no response” on missed response trials
  3.	Inter-trial interval: 4/6/8s (50%/25%/25%)<br>

*Trial Counts and other details:*<br>
64 experimental trials, random trial order<br>
Keyboard input: accepts “1” or “b” for “lower” guess, “2” or “y” for “higher” guess. Initial screens accept “t” to advance. “trigger” expects “t” to begin experiment.<br>
*How to interpret fields in output files:*<br>
“wait8.OnsetTime” stores clocktime of experiment start time (8s blank screen starts at this time)<br>
“input.Resp” stores response for each experimental trial (low=”1” or “b”, high=”2” or “y”). Empty if no response<br>
“input.RT” stores response time for each trial. 0 if no response.<br>
“procedure” stores trial condition (reward/punishment/neutral)<br>

## Also see (e.g., similar tasks described elsewhere):
Delgado, M.R., Nystrom, L.E., Fissell, C., Noll, D.C., & Fiez, J.A. (2000). Tracking the hemodynamic responses to reward and punishment in the striatum. Journal of Neurophysiology, 84(6): 3072-77. doi: 10.1152/jn.2000.84.6.3072

# v2-andoma — my recipe

**Source:** <GitHub link>   **License:** <from RECON.md>

## What I did to get it running (exact commands, in order)
```
```

## What broke and how I fixed it

## How I ran a game through the harness

## My one change (Week B)
I modified the eval_stm function to take another function as a parameter, I then passed it along the function chain using **kwargs.
This allowed me to pass my turing bot evaluation functions into the minimaxab bots to be used for evaluating board position rather then JUST the material difference of both sides. Allowing for more complex evalutation of positions.


## Results
See `results.csv` in this folder.


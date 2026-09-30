# SPMSP Instances

Repository containing E-VSP instances as used in:
```
C. Loman, L. Pascual, B. Elderhorst, J.M. van den Akker, R.W. van den Broek, J.A. Hoogeveen. Robust Parallel Machine Scheduling: A Comparison
of Robustness Measures and Local Search Approaches.
```

### `aj-br-cm.txt`
instance file for instance with a jobs, b precedence constraints and c machines. The structure of the file is built up as follows:
```
line 0: n (number of jobs)
line 1: m (number of machines)
line 2: r (number of precedence constraints)
line 3: deadline
line 4: processing times
line 5: release dates
lines 6-end: precedence relations
```

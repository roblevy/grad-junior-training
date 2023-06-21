# CLI Wrapper for wttr.in

This is (the world's worst) CLI wrapper for the excellent [wttr.in](https://github.com/chubin/wttr.in).

We're going to use it as a place to practice resolving merge conflicts.

NOTE: There's already a CLI wrapper around `wttr.in` but we're going to pretend
that there isn't.

## Exercise

Work in pairs, one of you is A, the other B. Decide this now.

A creates a branch named after you both, like this:

```
gcb rob-someoneelse
gpsup
```

B pulls the branch like this:

```
gl
gsw rob-someonelse  # TAB-completion is your friend here
```


### Exercise 1

A adds the following packages to the imports:

```
from random import random
from textwrap import dedent
```

Commit and push your changes.


B sorts the _current_ imports alphabetically.

Commit your changes then pull A's changes.
Resolve the merge conflict together.


### Exercise 2

Some of the command-line arguments don't work yet. Let's implement them, and
resolve any resulting merge conflicts.

A implements "One-line output"

B implements "Data rich output format"

B commits and pushes.

A commits and pulls B's changes.

Resolve the merge conflicts together.


### Exercise 3

A adds a `def __repr__(self):` function to WeatherChecker. 
B adds a `def __str__(self):` function.

How can you both add your functions and guarantee no merge conflicts?

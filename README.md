# python-paths


The sublime beauty of just running your own damn code in python.

One of the most fundamental tasks every programmer has to do at some point is to run some code they wrote from somewhere else. Typically, one writes a helper function, and you want to use it from a different program. In C++ land, this is as simple as `#include` ing your code, which simply copies and pastes your code. Crude, but easy to understand, and it works. 

In the following section I compare how easy it is to do this task in MATLAB and python, two commonly used languages in research computing. 

To be clear, the task we want to accomplish is this:

- We have some code X in location XX (on our local computer)
- We are working on code Y in location YY (also on our local computer)
- We want to use X in Y. 

| MATLAB | python |
| ---- | ---- |
| `cd /path/to/X/` <br> `addpath(pwd)` <br> `cd /path/to/Y/` And run your code  | | 



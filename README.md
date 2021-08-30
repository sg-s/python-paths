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
| `cd /path/to/X/` <br> `addpath(pwd)` <br> `cd /path/to/Y/` And run your code  | <img width="679" alt="1" src="https://user-images.githubusercontent.com/6005346/131398199-dde19c8a-9171-483d-b0e3-4aee043ec3b4.png">
<img width="690" alt="2" src="https://user-images.githubusercontent.com/6005346/131398206-9d80492b-b1af-4e1b-ba8c-abec10c5c29b.png">
<img width="668" alt="3" src="https://user-images.githubusercontent.com/6005346/131398209-9cc87b92-f41b-4c8b-9296-87276ddbe8c6.png">
) | 



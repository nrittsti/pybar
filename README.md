# pybar
A simple python 3 terminal progress bar.  
Created with 12 lines of code in a single module file.  
This progress bar can be used to display the progress of a long
running task, providing a visual feedback to the end-user.

## Usage

```python
#!/usr/bin/python
# -*- coding: UTF-8 -*-

from pybar import show_progress
from time import sleep

total = 100

for i in range(1, total + 1):
    show_progress(i, total, "a long running task")
    sleep(0.01)
```
## Sample output

 68.0% |████████████████████__________| a long running task

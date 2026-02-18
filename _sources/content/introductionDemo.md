# Title of the Introduction

## Subheading example A)

### Subsubheading A.1)

* First list
  - Item 1
  - Item 2
    - Item 3



"""{note}
Note here
"""

'''{dropdown}
This is a dropdown
'''
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

t = np.arange(0, 2*np.pi, 0.01)
x = 5
phi = 0.2
y = np.sin(t * x + phi)

plt.plot(t,y)

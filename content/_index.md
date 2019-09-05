---
description: A multi-algorithm, multi-timescale, multi-spatial-representation biochemical simulation environment.
---

# Hello E-Cell4

E-Cell System is a software platform for modeling, simulation and analysis of complex,
heterogeneous and multi-scale systems like the cell.

```python
from ecell4 import *

with reaction_rules():
    A + B == C | (0.01, 0.3)

run_simulation(10, {'A': 60, 'B': 60}, solver='gillespie')
```

![gillespie](images/gillespie.png)


# Features

### Single particle simulations

This is a description about feature1.
[The enhanced Green's Function Reaction Dynamics (eGFRD) method](http://gfrd.org),
[Spatiocyte](http://spatiocyte.org),
and the Reaction Brownian Dynamics(RBD) method.

### Multi-algorithm support

This is a description about feature2.

### Rule-based modeling

This is a description about feature3.

### Python programmable

This is a description about feature4.

### Interactive visualizations on Jupyter Notebook

This is a description about feature5.

### Bioinformatics integration

Garuda gadget, data source, etc.


# Examples

![drosophila](images/drosophila.png)

![minde](images/minde.gif)

This is a screenshot about example3.

[notebook](.)

![attractors](images/attractors.png)


For more tutorials and examples, see http://ecell4.readthedocs.io/.

## License

This project is licensed under the terms of the GNU General Public License v2.
See [LICENSE](https://github.com/ecell/ecell4#licensing-terms).

![RIKEN_logo](https://upload.wikimedia.org/wikipedia/en/d/dc/RIKEN_logo.gif)

# utils

Reusable code shared across notebooks. 

- `statevector_sim.py` *(planned)*: minimal NumPy state-vector simulator, with single-qubit gates, CNOT, tensor products, and measurment sampling. Every gate is checked against Qiskit's `Operator` and `Statevector`. 

Import it in a notebook with:

```python
import sys; sys.path.append("..")
from utils.statevector_sim import *
```
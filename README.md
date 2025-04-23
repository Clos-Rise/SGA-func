# SGA (Smooth Gaussian Activation)

Простая , легкая , функция активации для нейронных сетей. Выглядит следующиим образом : g(x)=x⋅e^−αx2.

Для Python :

<pre> python import numpy as np
def SGA(x, alpha=0.1):
          return x * np.exp(-alpha * x**2) </pre>

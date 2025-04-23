\documentclass{article}
\usepackage{listings}
\usepackage{xcolor}

\lstset{
    language=Python,
    basicstyle=\ttfamily\small,
    keywordstyle=\color{blue},
    commentstyle=\color{gray},
    stringstyle=\color{red},
    showstringspaces=false,
    frame=single,
    breaklines=true
}

\begin{document}

# SGA (Smooth Gaussian Activation)

Простая , легкая , функция активации для нейронных сетей. Выглядит следующиим образом : g(x)=x⋅e^−αx2.

Для Python :

\begin{lstlisting}
import numpy as np

def SGA(x, alpha=0.1):
    return x * np.exp(-alpha * x**2)
\end{lstlisting}

\end{document}

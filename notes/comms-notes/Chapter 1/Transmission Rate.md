We can measure how efficient our transmission of data is via the following formula
$$
rate = \frac{bits}{sec}
$$
### End-To-End Transmission
It is possible for a connection to be affected for more than one variable, for the context of these notes, we can see this as

$$d_{end-end} = N(d_{proc} + d_{trans} + d_{prop})$$
Where $d_{proc}$ is meant for processing the data, $d_{trans}$ is for transmission, and $d_{prop}$ is for propagation, while not really how it works in reality, we can think of $d_{proc}$ as a millisecond constant. As for the other two, we can calculate them with the following formulas:
$$d_{trans} = \frac{L}{R} ; \begin{cases}
L = packet \ length \\
R = bandwith
\end{cases}$$
$$d_{prop} = \frac{d}{s} ; \begin{cases}
d = Length \ to \ be \ traversed  \\
s = Speed \ of \ traversal
\end{cases}$$
And N is the number of routers involved minus one.
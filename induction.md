For all integers $n > 10$, $n - 2 < \frac{n^2 - n}{12}$

Base Case $n = 11$

$11 - 2 < \frac{11^2 - 11}{12}$\
$9 < 9.166$ (True)

Inductive Step\
Assume for some $k > 10$\
$k - 2 < \frac{k^2 - k}{12}$

Show for $k + 1$:\
$(k + 1) - 2 < \frac{(k + 1)^2 - (k + 1)}{12}$

$k - 1 < \frac{k^2 + k}{12}$

Proof:\
$k - 2 < \frac{k^2 - k}{12}$  
Add 1 to both sides:  
$k - 1 < \frac{k^2 - k}{12} + 1$

$\frac{k^2 - k}{12} + 1 \leq \frac{k^2 + k}{12}$ 
$1 \leq \frac{2k}{12} \implies 6 \leq k$\
Since $k > 10$, this holds.  

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

For all integers $n >= 1$, $\sum_{i=1}^{n} \sqrt{i} > \frac{2n\sqrt{n}}{3}$\
Base Case $k = 1$\
$\sum_{i=1}^{1} \sqrt{i} = \sqrt{1} = 1$\
$\frac{2\cdot1\sqrt{1}}{3} = \frac{2}{3}$\
$1 > \frac{2}{3}$\
Inductive step:\
$\sum_{i}^{k+1} \sqrt{i} > \frac{2(k+1)\sqrt{k+1}}{3}$\
$\sum_{i}^{k+1} \sqrt{i} = \sum_{i=1}^{k} \sqrt{i} + \sqrt{k+1} > \frac{2k\sqrt{k}}{3} + \sqrt{k+1}$\
$\frac{2k\sqrt{k}}{3} + \sqrt{k+1} >= \frac{2(k+1)\sqrt{k+1}}{3}$\
$\frac{2k\sqrt{k} + 3\sqrt{k+1}}{3} >= \frac{2(k+1)\sqrt{k+1}}{3}$\
$2k\sqrt{k} + 3\sqrt{k+1} >= 2(k+1)\sqrt{k+1}$\
$2k\sqrt{k} >= 2(k+1)\sqrt{k+1} - 3\sqrt{k+1}$\
$2k\sqrt{k} >= 2(k+1)\sqrt{k+1} - 3\sqrt{k+1}$\
$2k\sqrt{k} >= (2k -1)\sqrt{k+1}$\
$4k^2k >= (4k^2 - 4k + 1)*(k+1)$\
$4k^3>= 4k^3 - 3k+1$\
$0>=-3k + 1$\
$3k >= 1$\
$k >= \frac{1}{3}$\
$k >= 1$

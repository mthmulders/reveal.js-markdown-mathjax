## Slide title

1. Select two prime numbers: $p = 11, q = 17$
1. <!-- .element: class="fragment" -->Calculate _product_: $p * q = 187$
1. <!-- .element: class="fragment" -->Select random number < product: $e = 3$
1. <!-- .element: class="fragment" -->Find _d_, so that $(d * e) − 1 \mod (p − 1) * (q − 1) = 0$
   1. <!-- .element: class="fragment" -->$(d * 3) − 1  \mod (10 * 16) = 0$
   1. <!-- .element: class="fragment" -->$320 \mod 160 = 0$
   1. <!-- .element: class="fragment" -->$(321 - 1) \mod 160 = 0$
   1. <!-- .element: class="fragment" -->$(107 * 3) = 321 \Rightarrow $$d = 107$

<!-- .element: class="fragment" -->_Note_ that $d$ varies with $e$: when $e = 75, d = 183$.
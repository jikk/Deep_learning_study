w = learn_perceptron(neg_examples_nobias,pos_examples_nobias,w_init,w_gen_feas);

## 20170106

* Q: what is the *A generously feasible weight vector*?
  - Defined from lec2.pdf page 23.
  ```
  Every time the perceptron makes a mistake, the squared distance to all of 
  these generously feasible weight vectors is always decreased by at least the 
  squared length of the update vector.
  ```

## Using Deep learning for solving sudoku

**Bold** Alex Powell, Adit Suvarna, Wenqi Shi, GianGiacomo Navarra, Sivapriya Vellaichamy

### INTRODUCTION

With Machine learning outperforming humans in a varietyof games like Atari and Go, we were curious to explore howbig  a  challenge  is  the  logic  based  number  game  -  Sudoku.Logic  based  games  like  Sudoku  have  been  shown  shownto  help  delay  neurological  disorders  like  Alzheimer’s  anddementia.  However  the  game  is  easy  to  learn  but  hard  tomaster.

### PROBLEM DEFINITION

The object of Sudoku is to fill out each puzzle with numbers1-9 in a way that we only use each number once in each row,column and grid of the puzzle. In solving Sudoku players relayon  both  the  temporal  and  position  dependency  between  thenumbers on the board. Based on this facts we decide to solvethe  Sudoku  using  different  machine  learning  methods  likeConvolutional Neural Network (CNN) and a deep Q learningapproach. The purpose of the proposal is to use Machine Learning tosolve a Sudoku puzzle. The pipeline of the problem involvesusing  unsupervised  algorithm  to  detect  digits  and  furtherfeeding the recognised digits to Deep Learning models, whichwould be trained to solve the puzzle.

![Flowchart of proposed method.](https://github.com/ProjectCS7641/CS7641G8/blob/gh-pages/figure.PNG)

### DATASET
We  consider  as  adata source https://www.kaggle.com/bryanpark/sudoku

### METHODS

We   plan   to   present   the   results   of   handwritten   digitrecognition on MNIST dataset using state-of-art unsupervisedfeature  extraction  and  classification  techniques.  On  the  onehand, we aim to implement unsupervised clustering algorithmslike k-means, spectral clustering, DBSCAN, etc., use commonmetrics  to  evaluate  cluster  performance,  and  visualize  high-dimensional  cluster  centroids.  On  the  other  hand,  we  willalso train different types of auto-encoders to classify MNISTdigits. We will evaluate all the variants of the standard auto-encoder  on  the  basis  of  the  MNIST  benchmark  handwrittendigit  dataset  and  select  the  best  classifier. 

Two  deep  learning  techniques  are  considered:  a  AlexNetNetwork  and  a  deep  q  learning  method.  For  class  labelswe  want  to  use  an  indicator  function  to  denote  whetheror  not  the  chosen  label  t  is  equal  to  class  k.  Then  forlearning  both  architectures  utilizes  the  adaptive  momentumestimator  (Adam)  optimizer.  The  Adam  optimizer  involvesusing  the  first  and  second  moments  of  the  gradients.  The first  moment  involves  the  exponentially  decaying  average  ofprevious squared gradients. The Adam optimizer then uses thecombined averages of previous gradients to better update theparameters.

### RESULTS AND DISCUSSION

We  plan  to  analyze  the  accuracy  obtained  with  the  neuralnetworks  so  to  compare  their  performance  in  completing  thesudoku. We expect the accuracy to increase with the numberof layers but in order to avoid overfitting we will have to tunethe right number of layers to use. A metric we will utilize toevaluate a Deep Q-Learning network will be number of nodesexpanded during a best-first search.

### REFERENCES
[1] R. ”How to Build a Vision-Based Smart Sudoku,”
[2] Bharti, Drsantosh & Babu, Korra & Jena, Sanjay. (2015). Parsing-based Sarcasm Sentiment Recognition in Twitter Data.10.1145/2808797.2808910.
[3] Suresh Merugu, Azhar Talha Syed, (2015) Augmented  Reality  onSudoku   Puzzle   using   Computer   Vision   and   Deep   Learning.   In-ternational  Journal  of  Innovative  Technology  and  Exploring  Engi-neering  (IJITEE)ISSN:  2278-3075,  Volume-8,  Issue-11S2,  Septem-ber 2019 JoishJoish Bosco https://www.cloras.com/blog/solve-sudoku-using-depth-first-search/

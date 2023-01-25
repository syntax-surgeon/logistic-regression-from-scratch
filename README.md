# logistic-regression-from-scratch

> Designing a simple logistic regression algorithm from scratch, without the use of external ML libraries.<br>_(current version: 0.1)_
>
> #### Author: _Siddharth Yadav (syntax-surgeon)_

### main.ipynb

- Contains version-0.1 of the main program which tries to implement a **logistic regression algorithm**
- The core of the algorithm is based on an intuitive implementation of basic **gradient descent** combined with a non-linear function (sigmoid)
- The current version of the codebase is functional, however, future versions may be OOP-based
- Simple plotting functionality is included to visualize the results of the training

> #### Figure showing the dataset with the final classifier (left) and the mean log loss error per epoch (right)
>
> ![alt text](https://github.com/syntax-surgeon/logistic-regression-from-scratch/blob/main/readme_assets/training_plot.png?raw=true)

#### Features planned for release 1.0

- Converting the codebase to an OOP architecture
- Inclusion of additional classifier training features such as _'strict_reduce'_ and _'descent_type'_
- Advancing the graphing/plotting functionality to include intermediate perceptrons
- Increasing the verbosity of the in-code documentation

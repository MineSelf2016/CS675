## NJIT CS 675

Machine learning is a practice-driven course, here try to note down the assignments of the courses.

I will update the homework before or after the submission deadline.


Useful material: <a href="https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf">Matrix cookbook</a>

### Homework 1

For Task 2, use plain method or normal equation to fit the function of the line.

plain method:

> Step 1: for each point (x, y), calculate $\sum{x}$, $\sum{y}$, $\sum{x^2}$, and $\sum{xy}$
>
> Step 2: the slope $k=\frac{N\sum{xy} - \sum{x}\sum{y}}{N\sum{x^2}-(\sum{x})^2}$, the intercept $b=\frac{\sum{y}-k\sum(x)}{N}$
>
> Step 3: the function of the line $y=kx+b$
>
> Done!

normal equation:
> $w = (X^T X)^{-1}(X^T y)$
>
> $y=w_1x+w_0$


For Part 2, explore dataset, please install the scikit-learn package before version 1.2, by using the command

```bash
pip install scikit_learn<1.2
```

or

```bash
conda install scikit_learn<1.2
````

you can explore the whole support version at https://scikit-learn.org/dev/versions.html

Then, make sure to select the correct python interpreter not matter in Colab or in local environment.
# Optimization frameworks in matlab
## 1 - CVX
### 1 - 1 - What kind of problems can cvx solve?
[Before using cvx tool, read this first!](http://ask.cvxr.com/t/why-isnt-cvx-accepting-my-model-read-this-first/570)
CVX is specifically designed for certain kinds of convex optimization problems, as well as certain mixed-integer convex models and geometric programs. If you do not already know that your problem fits into one of CVX’s supported problem classes, then CVX is not the correct tool to use. All in all, there are in general three kinds of problems can be addressed by CVX tool:
+ certain kinds of convex problems,
+ certain kinds of mixed-integer models,
+ geometric programs.
### 1 - 2 - The procedures of using CVX.
First, check the convexity of your model. Second, express your model in terms of these [functions](http://web.cvxr.com/cvx/doc/funcref.html) and avoid [DCP errors](http://web.cvxr.com/cvx/doc/dcp.html).
See [quick start](http://cvxr.com/cvx/doc/quickstart.html) for more information.
## 2 - YALMIP
[YALMIP](https://yalmip.github.io/) is a modeling framework in MATLAB that supports both convex and non-convex problems, and it connects to a wider variety of solvers than CVX. So that might be worth a try if you want to stay in MATLAB. And of course, MATLAB has an optimization toolbox of its own. 

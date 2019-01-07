7 Simple Steps To Visualize And Animate The Gradient Descent Algorithm

https://jed-ai.github.io/py1_gd_animation/

How to plot 2D gradient(rainbow) by using matplotlib?
https://stackoverflow.com/questions/43823686/how-to-plot-2d-gradientrainbow-by-using-matplotlib

7 Simple Steps To Visualize And Animate The Gradient Descent Algorithm
https://jed-ai.github.io/py1_gd_animation/

Numerical gradient for nonlinear function in numpy/scipy
https://stackoverflow.com/questions/46641453/numerical-gradient-for-nonlinear-function-in-numpy-scipy

import numpy as np

# Hock & Schittkowski test problem #40
x = np.mgrid[0.75:0.85:0.01, 0.75:0.8:0.01, 0.75:0.8:0.01, 0.75:0.8:0.01]
# target is evaluation at x = [0.8, 0.8, 0.8, 0.8]
f = -x[0] * x[1] * x[2] * x[3]
g = np.gradient(f)

print g

Gradient descent
https://en.wikipedia.org/wiki/Gradient_descent#MATLAB

Gradient descent with Python
by Adrian Rosebrock on October 10, 2016 in Deep Learning, Machine Learning, 
https://www.pyimagesearch.com/2016/10/10/gradient-descent-with-python/

Multivariate Linear Regression in Python WITHOUT Scikit-Learn
https://medium.com/we-are-orb/multivariate-linear-regression-in-python-without-scikit-learn-7091b1d45905

TRY JUPYTER
http://jupyter.org/try

优化器(optimizer)是编译Keras模型
https://keras.io/zh/optimizers/

Visualizing the gradient descent method
https://scipython.com/blog/visualizing-the-gradient-descent-method/


Transportation Problem

https://scipbook.readthedocs.io/en/latest/intro.html

Linear Optimization


We begin with a simple linear optimization problem; 
https://scipbook.readthedocs.io/en/latest/intro.html


The complete program for solving our model can be stated as follows:

from pyscipopt import Model

model = Model("Simple linear optimization")

x1 = model.addVar(vtype="C", name="x1")
x2 = model.addVar(vtype="C", name="x2")
x3 = model.addVar(vtype="C", name="x3")

model.addCons(2*x1 + x2 + x3 <= 60)
model.addCons(x1 + 2*x2 + x3 <= 60)
model.addCons(x3 <= 30)

model.setObjective(15*x1 + 18*x2 + 30*x3, "maximize")

model.optimize()

if model.getStatus() == "optimal":
    print("Optimal value:", model.getObjVal())
    print("Solution:")
    print("  x1 = ", model.getVal(x1))
    print("  x2 = ", model.getVal(x2))
    print("  x3 = ", model.getVal(x3))
else:
    print("Problem could not be solved to optimality")


Monte-Carlo

https://oldwww.kdais.gov.tw/exper/exp23-1/23-1-3.pdf

Using Lagrange multipliers in optimization

http://kitchingroup.cheme.cmu.edu/blog/2013/02/03/Using-Lagrange-multipliers-in-optimization/


Methods for Constrained Optimization
Numerical Optimization Lectures
https://courses.maths.ox.ac.uk/node/view_material/1377

Constrained Optimization and Lagrange Multiplier Methods
http://www.mit.edu/~dimitrib/lagr_mult.html

http://www.mit.edu/~dimitrib/Constrained-Opt.pdf

optimization problem mutiplier method
https://cims.nyu.edu/~donev/Teaching/NMI-Fall2010/Lecture7.handout.pdf

Github with MathJax (Chrome extesion) https://github.com/orsharir/github-mathjax GitHub with MathJax

Evolutionary Algorithms Library (EAL)
https://github.com/mlagunas/evolutionary_algorithms

Python, numerical optimization,
genetic algorithms
http://daviderizzo.com/blog/wp-content/uploads/2010/05/Python-numerical-optimization-genetic-algorithms.pdf


INSTALLATION:
Official release available at Chrome Web Store.

The function $f(x)=x^2$ 

$$\int_{a}^{b} f(x) dx=\int_{a}^{b} x^2 dx=\sum_{n=1}^{\infty} 2^{-n}  $$


https://happycoder.org/2017/10/07/python-data-science-and-machine-learning-tutorial-introduction/


ConvNetJS is a Javascript library for training Deep Learning models (Neural Networks) entirely in your browser. Open a tab and you're training. No software requirements, no compilers, no installations, no GPUs, no sweat.
https://cs.stanford.edu/people/karpathy/convnetjs/?spm=5176.100239.blogcont43089.256.HCgoHQ

MIT 6.S094: Deep Learning for Self-Driving Cars
https://selfdrivingcars.mit.edu/

# Numerical_Analysis
Numerical_Analysis
numerical analysis python pdf
https://www.google.com.tw/search?source=hp&ei=rq04W7LrJojG0ATHrbzADA&q=numerical+analysis+python+pdf&oq=numerical+ananlysis+python+&gs_l=psy-ab.1.0.0i19k1j0i13i30i19k1j0i8i13i30i19k1l4.2739.16195.0.21864.31.29.1.0.0.0.383.2788.23j4j0j1.29.0....0...1.1.64.psy-ab..1.30.2914.6..0j35i39k1j0i131k1j0i10i203k1j0i8i13i30k1j0i13k1j0i13i30k1.105.-xAg-apO-i4

What a Deep Neural Network thinks about your #selfie

http://karpathy.github.io/2015/10/25/selfie/

MIT 6.S094: Introduction to Deep Learning and Self-Driving Cars
https://www.youtube.com/watch?v=1L0TKZQcUtA   4:20

Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
https://github.com/karpathy/convnetjs
             
Submission for the MIT self-driving car project on deep reinforcement learning
https://github.com/jasonsalas/deeptraffic

陳宏瑋   https://github.com/tewqkop111/w3_test/blob/master/

林一忻   https://github.com/bonnielin1111/bonnielin1111/blob/master/

江浩越   https://github.com/Jonehy/na10630622/blob/master/
             
馬露西   https://github.com/marylucy04/NAclassw3/blob/master/           

喬芮珂   https://github.com/RikkeKJakobsen/classw3/blob/master/

廖翌翔   https://github.com/YI-XIANG/class/blob/master/

黃鉑衽   https://github.com/Huangboran/Bo-ran-python-work/blob/master/

管維凱   https://github.com/s10730609/python/blob/master/
       
鐘建民   https://github.com/misakimeidaisuki/num_py_homework/blob/master/test5_10730612.ipynb

林育陞   https://github.com/S10730614/python/blob/master/

李世鈞   https://github.com/hugi8505/The_cintegral/blob/master/

賴奕鈞   https://github.com/s10730617/hw/blob/master/

張永霖   https://github.com/YONG-LIN/Lin/blob/master/

邱俊邑   https://github.com/eeehh113/work/blob/master/

顏辰祐   https://github.com/Tiingx113/Value-Analysis/blob/master/Test5_10730620.ipynb

林培誌   https://github.com/scott608/test/blob/master/

黃懷逸   https://github.com/10730623/123456/blob/master/             

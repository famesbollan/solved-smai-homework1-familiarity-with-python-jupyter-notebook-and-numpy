Download Link: https://assignmentchef.com/product/solved-smai-homework1-familiarity-with-python-jupyter-notebook-and-numpy
<br>
Familiarity with Python, Jupyter Notebook, and Numpy/SciPy/Matplotlib

The goal of this problem is to set up the coding environment and go through the basics of Python, NumPy, SciPy, and Matplotlib. For this, you are provided with the “Tutorial-1.ipynb” file that you are required to go through.

Throughout the course, we will be using Python as our choice of programming language and will be <em>Notebooks </em>to demonstrate code. Python is a highlevel, dynamically typed multiparadigm programming language. Python code is often said to be almost like pseudocode, since it allows you to express very powerful ideas in very few lines of code while being very readable.

In the course, we will be assuming a basic familiarity with the Python programming language and will be using ‘python3’, specifically any version <em>&gt; </em>3<em>.</em>6<em>.</em>0. You can check your Python version by typing ‘python –version’. If not already installed in your system, a recommended way to install python is via installing the latest version of ‘anaconda’ or ‘miniconda’ (see – anaconda: <a href="https://docs.anaconda.com/anaconda/install">https://docs.anaconda.com/anaconda/install</a> miniconda: <a href="https://docs.conda.io/en/latest/miniconda.html">https: </a><a href="https://docs.conda.io/en/latest/miniconda.html">//docs.conda.io/en/latest/miniconda.html</a><a href="https://docs.conda.io/en/latest/miniconda.html">.</a> If you have an independent installation or you are using ‘miniconda’, ensure that you have the following basic libraries installed:

<ol>

 <li>Python ≥ 3.6.0 (with ‘pip’ – should be automatically present);</li>

 <li>NumPy (<a href="https://numpy.org/install">https://numpy.org/install</a><a href="https://numpy.org/install">)</a>;</li>

 <li>Scipy (<a href="https://www.scipy.org/install.html">https://www.scipy.org/install.html</a><a href="https://www.scipy.org/install.html">)</a>;</li>

 <li>Pandas (<a href="https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html">https://pandas.pydata.org/pandas-docs/stable/getting_s</a>tarted/ <a href="https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html">html</a><a href="https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html">)</a>;</li>

 <li>Jupyter Notebook (<a href="https://jupyter.org/install">https://jupyter.org/install</a><a href="https://jupyter.org/install">)</a>;</li>

 <li>Scikit Learn (<a href="https://scikit-learn.org/stable/install.html">https://scikit-learn.org/stable/install.html</a><a href="https://scikit-learn.org/stable/install.html">)</a>;</li>

 <li>seaborn (<a href="https://seaborn.pydata.org/installing.html">https://seaborn.pydata.org/installing.html</a><a href="https://seaborn.pydata.org/installing.html">)</a>.</li>

</ol>

We will be informing you along the way whenever more libraries are needed.

We will now briefly talk about <em>notebooks</em>. A Jupyter notebook lets you write and execute Python code locally in your web browser. Jupyter notebooks make it very easy to tinker with code and execute it in bits and pieces; for this reason they are widely used in scientific computing. In order to run the tutorial notebook provided, first ‘cd’ to the directory where the notebook file (“*.ipynb”) is present and then run ‘jupyter notebook’ in your terminal. This should automatically launch a notebook server at ‘http://localhost:8888’. Click on the ‘*.ipynb’ and to finally run the notebook. In order to close a notebook, you need to save and quit the notebook and shutdown the notebook session(s) from the menu. Alternatively, you can press ‘Ctrl+c’ twice in the terminal. For this tutorial, you need to run the “Tutorial-1.ipynb” file.

<strong>Optional Reading</strong>: You can check out (i) <a href="https://numpy.org/doc/1.18/numpy-user.pdf">https://numpy.org/doc/1.18/ </a><a href="https://numpy.org/doc/1.18/numpy-user.pdf">numpy-user.pdf</a><a href="https://numpy.org/doc/1.18/numpy-user.pdf">;</a>(ii) <a href="https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf">https://sites.engineering.ucsb.edu/</a><a href="https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf">~</a><a href="https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf">shell/che210d</a>/ <a href="https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf">numpy.pdf</a><a href="https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf">;</a> and (iii) <a href="https://github.com/rougier/numpy-tutorial">https://github.com/rougier/numpy-tutorial</a><a href="https://github.com/rougier/numpy-tutorial">.</a>

<h1>2           NumPy exercise</h1>

Write the code for the following:

Consider two sets of points <em>p</em><sub>0 </sub>and <em>p</em><sub>1 </sub>describing a line in a 2-Dimensional (2D) plane. Consider an arbitrary point <em>p </em>in 2D.

<ol>

 <li>Compute the orthogonal distance between the point <em>p </em>and the the line segment joining the points <em>p</em><sub>0 </sub>and <em>p</em><sub>1</sub>.</li>

 <li>Plot the line segment joining the points <em>p</em><sub>0 </sub>and <em>p</em><sub>1</sub>, the point <em>p </em>and the orthogonal distance between the point and the line segment.</li>

</ol>

<h1>3           Linear Algebra</h1>

<ol>

 <li>Suppose that <strong>u </strong>∈ R<sup>3 </sup>is a vector which lies in the first quadrant of the <em>xy</em>-plane and has a length 3 and that <strong>v </strong>∈ R<sup>3 </sup>is a vector that lies along the positive <em>z</em>-axis and has a length 5. Then,

  <ul>

   <li>||<strong>u </strong>× <strong>v</strong>|| =</li>

   <li>The <em>x</em>-coordinate of <strong>u </strong>× <strong>v </strong>is0 (choose <em>&lt;</em>, <em>&gt;</em>, or =) ;</li>

   <li>The <em>y</em>-coordinate of <strong>u </strong>× <strong>v </strong>is0 (choose <em>&lt;</em>, <em>&gt;</em>, or =) ;</li>

   <li>The <em>z</em>-coordinate of <strong>u </strong>× <strong>v </strong>is0 (choose <em>&lt;</em>, <em>&gt;</em>, or =) ;</li>

  </ul></li>

</ol>

√

<ol start="2">

 <li>Suppose that <strong>u </strong>and <strong>v </strong>√are vectors in R<sup>7</sup>, both of length 2 2, and the</li>

</ol>

length of <strong>u </strong>− <strong>v </strong>is also 2 2. Then,

<ul>

 <li>||<strong>u </strong>+ <strong>v</strong>|| = ; (b) The angle between <strong>u </strong>and <strong>v </strong>is .</li>

</ul>

<ol start="3">

 <li>Consider the following matrix where <em>a </em>is a real number.</li>

</ol>

<ul>

 <li>For what values of <em>a </em>will a row interchange will be required during Gaussian elimination process? Answer: <em>a </em>= .</li>

 <li>For what values of <em>a </em>is the matrix singular? Answer: <em>a </em>= .</li>

</ul>
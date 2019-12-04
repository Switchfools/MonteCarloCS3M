# MonteCarloCS3M
Author: Nicolás Vergara, Based on the work of Prof. Frank Pollmann, Prof. Michael Knap, Johannes Hauschild from TUM. 
This a series of execises developed for the 2nd Colombian School on Magnetism and Magnetic Materials (CS3M) 2019, in order to understand how to apply montecarlo methods to the simulation of Magnetic Materials. The exercises will be based on python.
## Setup 
If you are completely new to python, a good introduction for our course are the scipy lectures  If you have a laptop, a very good python distribution is provided by Anaconda, available at https://www.anaconda.com/download. It ships with jupyter, uses Intel MKL and comes with the numba package.   The [numba package](http://numba.pydata.org/) is used in some of the codes for optimization. This brings in some cases a speed up of up to 100, installing numba is therefore highly recommended.  If you really have big trouble installing numba, or find the error messages produced by it too confusing,  you can copy the file `numba.py` providing a dummy `@jit` decorator into the other folders.  The price is that you loose the speed-up... To start a jupyter notebook, follow these steps: 
1. Open a terminal
2. Go to the directory where you keep your scripts/notebooks using `cd some/directory` 
3. On your laptop, enter `jupyter notebook`. This should start a local server opening a webpage in the browser (e.g. firefox), where you can create python notbooks etc.    If you close the web page by accident, open the page http://localhost:8888/  
4. Do your calculations. 
5. Once you're done, stop the server in the terminal by pressing Ctrl-C and confirm with 'y'  We use the ipython magic `%matplotlib inline` to include plots showing the results directly in the notebooks. 
# Further references 
- Introduction to Python, https://www.scipy-lectures.org/ 
- Lecture Notes by Anders W. Sandvik, http://arxiv.org/abs/1101.3281v1

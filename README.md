# BioPy

#### Overview:
----
BioPy is a collection (in-progress) of biologically-inspired algorithms written in Python. Some of the algorithms included are more focused on artificial model's of biological computation, such as Hopfield Neural Networks, while others are inherently more biologically-focused, such as the basic genetic programming module included in this project. Use it for whatever you like, and please contribute back to the project by cleaning up code that is here or contributing new code for
applications in biology that you may find interesting to program.

NOTE: The code is currently messy in some places. If you want to make a Pull Request by tidying up the code, that would certainly be merged. Since most of this was written while in the middle of our (jaredmichaelsmith and davpcunn) Graduate Bio-Inspired computation course, there are some places where the code has diverged into a dark chasm of non-pythonic mess, despite the algorithms still performing very well. Contributions in this area are much appreciated!

#### Dependencies:
----
- NumPy
- SciPy
- Scikit-Learn
- Matplotlib

#### Categories
----
Below you will find several categories of applications in this project.

##### Neural Networks:
----
- Hopfield Neural Network
- Back Propagation Neural Network
    - Tests included:
        - XOR
        - Two Function Approximations
        - MNIST Handwritten Digits Recognition Test
            - From scikit-learn package
        - Fisher's Iris data set: http://en.wikipedia.org/wiki/Iris_flower_data_set
            - From scikit-learn package
        - Labelled Faces in the Wild Dataset: http://vis-www.cs.umass.edu/lfw/
            - From scikit-learn package, originally collected by the University of Mass. Amherst

##### Genetic Programming:
----
- Basic Genetic Computation Algorithm
    - Features:
        - "drag-n-drop" fitness functions  
        - crossover and mutation of genes
        - learning ability for offspring of each generation

##### Self-Organization and Autonomous Agents
----
- Particle Swarm Optimization
    - Features:
        - You can configure many of the parameters of the algorithm such as the velocity, acceleration, and number of initial particles, as well as several other parameters.


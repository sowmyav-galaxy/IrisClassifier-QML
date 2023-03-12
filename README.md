# QOSF-Assesment-Task-3

**Problem Statement**:
Generate a Quantum Support Vector Machine (QSVM) using the iris dataset and try to propose a kernel from a parametric quantum circuit to classify the three classes (setosa, versicolor, virginica) using the one-vs-all format, the kernel only works as binary classification. Identify the proposal with the lowest number of qubits and depth to obtain higher accuracy. You can use the UU† format or using the Swap-Test.

## Some Definitions

**Kernel Methods** - embedding data into a higher dimensional feature space [1] <br>

**Support Vector Machine** - in a feature space where the two classes of data can be linearly separable, SVM defines a linear boundary (representing a hyperplane) between the two classes [1] <br>

**Kernel Trick** - switch between different models that are created by defining kernel functions from the inner product of data points mapped on to the feature space [1] <br>

**Implicit Kernel** - use a classical model that relies on a kernel function and evaluate the kernel using a qunatum computer (inner product of quantum states in feature Hilbert space) [1]
<br>

**Explicit Kernel** - the quantum computer learns the linear decision boundary using a parameterized quantum circuit [1] <br>

**Parameterized Quantum Circuit** - quantum computer prepares quantum state based on certain parameters and measures the result, based on the outcome, a classical computer adjusts parameters in order to minimize a particular function (ie. loss function) [2] <br>

**Swap Test** - method to estimate implicit kernel based on encoder circuit and measure the overlap between two states [2] <br>

**One-vs-All Format** - in this example, for the three classes, there will be three separate binary classfiers each trained to answer only one classification question affirmatively or negatively; works best with few number of classes [3] <br>


## References
[1] Schuld and Killoran (2018) https://arxiv.org/pdf/1803.07128.pdf <br>
[2] Bendetti et al. (2019) https://arxiv.org/pdf/1906.07682.pdf <br>
[3] Google ML course https://developers.google.com/machine-learning/crash-course/multi-class-neural-networks/one-vs-all <br>

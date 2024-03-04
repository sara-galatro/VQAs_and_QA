# VQAs_and_QA
Repository with every file related to my Master's Thesis, "Solving systems of equations through quantum computing: from Variational Quantum Algorithms to Quantum Annealing". 

Main topics: quantum computing, variational algorithms, and quantum annealing <br>
Other topics: MQ problems and optimization problems

Supervisor: Prof. Marco Pedicini <br>
Co-Supervisor: Dr. Massimo Bernaschi


## Repository "GateModel_experiments"
This repository contains the Jupyter Notebooks and the auxiliary files concerning the experiments on the VQLS for linear systems [1] and the QAOA for the MQ problem with 5 bits (MQ5).
In more detail:
* The file "VQLS.ipynb" runs the VQLS using a local simulator. 
* The file "VQLS_QPU.ipynb" runs the VQLS on a QPU or on a local noisy simulator (default).
* The file "mq_with_qaoa.py" runs the QAOA algorithm to solve the MQ5 problem on a local simulator, both noiseless and noisy.
* The file "article_lib.py" is the library created using functions defined in the repository https://github.com/qiboteam/mq-problem-quantum-annealing by Sergi Ramos-Calderer and Ruge Lin for [2].


## Repository "QA_experiments"
This repository contains the Jupyter Notebooks and the auxiliary files (images and custom Python libraries) concerning the experiments on the MQ problems using Quantum Annealing.
In more detail:
* The file "1_iterative_comparison.ipynb" runs the iterative method proposed in [2] on the Pegasus and the Zephyr topologies. 
* The file "2_qubits_comparison.ipynb" runs the minor embedding routine on the two topologies to compare the physical qubits needed for both the penalty and the truncated encoding.
* The file "article_lib.py" is the library created using functions defined in the repository https://github.com/qiboteam/mq-problem-quantum-annealing by Sergi Ramos-Calderer and Ruge Lin for [2], while the file "my_lib.py" contains the functions I defined.


## Main references
[1] "Variational Quantum Linear Solver", by Carlos Bravo-Prieto, Ryan LaRose, M. Cerezo, Yigit Subasi, Lukasz Cincio, Patrick J. Coles, https://arxiv.org/abs/1909.05820 <br>
[2] "Solving systems of Boolean multivariate equations with quantum annealing", by Sergi Ramos-Calderer, Carlos Bravo-Prieto, Ruge Lin, Emanuele Bellini, Marc Manzano, Najwa Aaraj, and José I. Latorre, https://arxiv.org/abs/2111.13224

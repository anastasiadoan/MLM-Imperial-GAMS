Our project aims to explore the intersection of machine learning and optimization by sparsifying a neural network within the given timeline. Specifically, we'll work on setting as many weights to zero as possible without exceeding a specified accuracy drop on a validation set.
This project involves several challenges:

    Integrating a Neural Network with GAMSPy: Although we have OMLT integration coming up, I'll assist you with this part due to time constraints, we can hack something up quickly.

    Formulating the Optimization Model: In addition to putting the model, we need to put the data as well and come up with a model.

    MINLP Formulation: Exploring whether we can simplify this to an NLP formulation would be beneficial. 

    Solver Performance: GAMS is solver-agnostic, so we'll experiment with different solvers, compare their performance, and tune solver parameters. We'll also test if these tuned parameters work for other instances.

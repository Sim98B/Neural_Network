# Neural_Network
This repo has various handmade neural networks

1. 1 Layer Classifier: a simple 1 layer neural network to classify random generatyed data
   Random data are generated with make_blobs() which parameters can be adjusted to get easier/harder problems; the function generating    data also return a difficulty index of the task, based standard deviatiation of blobs and number of classes, between 0 and 1           repsectively the easiest and the hardest problem.
   
   The neural network has to minimize the cross entropy loss function and it returns the weights and the bias value to evaluate           model's    performance on data never seen, I.E. test set.
   
   The function provides numeric and graphic outcome about loss decreasing and a confusion matrix.
   
   Parameters: epochs = [**int**] number of learning epochs (defult = 200); lr = [**float**] learning_rate (default = 0.001); verbose = [**int**] verbosity, in epochs, for displaying loss decreasing (default = 10); bs = [**int**] batch size of the train set used to adjust weights and bias (default = 32); es = [**int**] number of epochs without a loss decrease beyond which learning is stopped (default = 30); dropout = [**float**] percentage of feature to drop and don't use during learning (default = 0.2); plot = [**0 or 1**] whether display train and validation loss decreasing and confusion matrix's plots (default = 1)

# DS410_final

### Instructions
You are to construct a .sh file that accomplishes the following things:

1. Installs a new conda virtual environment in ICDS. The name of this virtual environment should be "username_final" - so for example - "abc1234" if "abc1234" is your username.

2. Downloads and installs the third-party spark software here (in the new virtual environment): https://github.com/dmmiller612/sparktorch/tree/masterLinks to an external site.

3. Downloads the MNIST image classification dataset to csv (https://github.com/dmmiller612/sparktorch/blob/master/examples/mnist_train.csv). Look up the "wget" command to download from github.

4. Trains a deep CNN using the architecture defined here (with appropriate modifications) - https://github.com/dmmiller612/sparktorch/blob/master/examples/simple_cnn.pyLinks to an external site.. Note that the training will be distributed.

5. Provides all this code in a Github repository that can be used to git clone from ICDS.

Instructions

Name your .sh file as "username.sh" - this will be your only submission. Use 4 nodes and 4 tasks per node for your experiments. The instruction team will use the following command to reproduce your work:

"sbatch username.sh"

If your code does not execute out of the box (i.e., there is any error) - you will not receive any credit for the final exam.


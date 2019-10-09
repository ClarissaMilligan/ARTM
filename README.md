# ARTM
Repository for the Augmentations with Random Triplet Mining (ARTM) Clustering Method.

The paper was successfully submitted for the Geometric Deep Learning Workshop at ICLR. Our code is awaiting public release.

Access the paper here: https://drive.google.com/file/d/11ADht4hmCCN1hUuiP6l3pB3Tj3Uw1HJ1/view?usp=sharing


---------------
How to use ARTM
---------------

Clone the repository.

Run the startup.sh and install requirements found in requirements.txt (especially make sure torchvision version 0.2.2 is installed).

To run ARTM, navigate to the ARTM folder and run the run.py file using:
```
python run.py
```
To change to default values, you can add parameters.

For example,
<pre>
    To change the number of epochs,           add --num_epochs      (default is 1)
    To change the learning rate,              add --starting_lr     (default is 0.001)
    To change the data set,                   add --dset            (default is MNIST)*
    To change whether plots are displayed,    add --show_plots      (default is False)**
 </pre>
**Supported datasets include "MNIST", "FASHIONMNIST", and "CIFAR10".*

***Displays augmented images, distance histograms, and confusion matricies for accuracy.*

You can also change the augmentation values as well. For a complete list, please view the run.py file.

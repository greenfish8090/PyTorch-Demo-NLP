# PyTorch demo
This repo contains all the code for the PyTorch demo conducted as part of CS F429: Natural Language Processing.

# Code organization
## `pytorch_model.ipynb`
Contains the code for a very basic pytorch module. Meant to be a tutorial on how to build a neural network

## `training_mnist.ipynb`
Contains a full minimal training pipeline:
- dataset and dataloader initialization
- model creation
- training
- evaluation
<!-- -->
Note that this is meant to be demo of *PyTorch*, so practices like validation aren't used. You should use them in all your projects, however.
### Why MNIST and not an NLP dataset?
NLP is a sequence processing problem, and sequence models like transformers and RNNs are more involved than regular feed forward networks. I wanted to use a simple model that trains and produce results fast.
### Why not CNN?
Wanted to keep things simple. Moreover if I did use a CNN this might as well be a computer vision course demo :)

## `rnn.ipynb`
Contains code and illustrations that shed light into the inner workings of RNNs. Also shows how to implement manually in pytorch without using torch.nn.RNN\
Finally, it shows how to use the torch.nn.LSTM module\
After going through this, you should be able to train your own LSTM on whatever dataset you want.

## `transformer.ipynb`
Jk, out of scope for now. Coming soon maybe?

# Setting up
If you want to run this code,
1. [Install anaconda/miniconda](https://docs.anaconda.com/anaconda/install/index.html) and set it up
2. [Clone this repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to your local
3. In your anaconda/miniconda command prompt, run the following from the directory containing the cloned code:
    ```
    $conda env create --name <preferred_env_name> --file=environment.yml
    ```
4. Run:
    ```
    $conda activate <preferred_env_name>
    $jupyter notebook
    ``` 
5. A notebook should open on your browser and you'll be able to run everything.

You can use the same environment for your NLP course project as well.

# Contact
If you have any doubts/suggestions please email me f20190040@hyderabad.bits-pilani.ac.in

# Thanks for visiting!
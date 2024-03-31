# Speech Emotion Recognition (SER)
A Machine Learning project that aims to classify emotions from speech. The project uses the *Toronto Emotional Speech Set* (TESS) dataset, from the University of Toronto, to train and test the model. The model is trained using a Convolutional Neural Network (CNN) and a Recurrent Neural Network (RNN) to classify emotions from speech.

## Toronto Emotional Speech Set (TESS)
The dataset is a collection of 200 target words spoken by two female voice actors (aged 26 and 64 years) in seven emotional expressions (neutral, happy, sad, angry, fear, disgust, and surprised). To organize the files, we named the folders and files as either **OAF** (Old Adult Female) and **YAF** (Young Adult Female). 

The TESS dataset is available for free and can be downloaded from this [following link.](https://tspace.library.utoronto.ca/handle/1807/24487)


## Prerequisites
In order to run this project, you need to have the following installed on your machine:
- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install) (or alternatively just install [Anaconda](https://www.anaconda.com/download))

## Running Locally
1. Clone the repository
```bash
git clone https://github.com/cifelse/ser.git
```
2. At the root of the folder run the Main.ipynb file with your respective Jupyter Notebook environment (we personally prefer Anacoda)

> [!IMPORTANT]
> The notebook installs some additional but required packages and heavily relies on pip. Make sure you have pip installed and added to your PATH.

## References
- Pichora-Fuller, M. K.; Dupuis, K. (2020). Toronto emotional speech set (TESS). University of Toronto. https://doi.org/10.5683/SP2/E8H2MF
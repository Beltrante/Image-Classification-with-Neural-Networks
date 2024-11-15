<br />
<div align="center">
    <img src="images/logo.jpeg" alt="Logo" width="300" height="200">
  <h3 align="center">Neural Network for plant health classification</h3>
    <a href="NeuroNauti/Report.pdf"><strong>Project Documentation</a>
</div>

## Neural Networks and Deep Learning 2023/24

This repository hosts a project developed as part of the *Artificial Neural Networks and Deep Learning* course at Politecnico di Milano. 

The project received a score of 10 out of 10 points and its summary description is provided below as well as links to the original Codalab challenge page.

Additionally, this repository includes the hidden datasets utilized for the final grading of the project to provide all the data necessary for understanding the approaches and the final evaluation of the work.
- *The data MUST be downloaded before running the notebook from the links provided in the data folder.*

## Project description

- **[Plant Health Classification](https://codalab.lisn.upsaclay.fr/competitions/16245)**: 
The objective was to classify plants (like the one in the example image below) that were divided into two categories according to their state of health. It was a binary classification problem, so the goal was to predict the correct class label in {0, 1}.
<div align="center">
    <img src="images/plant.png" alt="Logo" width="160" height="160">
</div>

Various techniques are explored, including:
- Custom Convolutional Neural Networks tailored for our specific task.
- Utilization of pre-trained models from the Keras library like ConvNeXtLarge.
- Transfer learning and fine-tuning techniques, to adapt pre-trained models to the plant classification problem.

The project was implemented in Python utilizing the TensorFlow and Keras libraries, additional information can be found in the [report](NeuroNauti/Report.pdf) we submitted for evaluation or in the [notebook](NeuroNauti/Report.ipynb).

A final better version of the notebook was created after the challenge completion and is available [here](an2dl-ch1-complete.ipynb).

This final version was able to reach an impressive Accuracy of *0.911* in the hidden test dataset

## Data structure

The Data for this project should be downloaded and extracted in the data folder from the following link:
- [full_ch1_data](https://www.beltrante.it/matteo/data1/data1.zip) (or from [Kaggle](https://www.kaggle.com/datasets/matteobeltrante/an2dl-ch1-data) if you are authorized)

The complete folder MUST have the following structure

    ├── this dir
        ├── data                        # Data dir
            ├── public_data.npz         # Challenge data 
            ├── public_test.npz         # Phase1 eval data
            ├── private_test.npz        # Phase2 eval data

## Acknowledgments

The model in this directory has been developed by the *NeuroNauti* team, composed by:

* [Matteo Beltrante](https://github.com/Beltrante)
* [Lorenzo Rossi](https://github.com/lorossi)

In the context of the course [Artificial Neural Networks and Deep Learning](http://chrome.ws.dei.polimi.it/index.php?title=Artificial_Neural_Networks_and_Deep_Learning) at @PoliMi (Politecnico di Milano), AY2023/24.

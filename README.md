# VGG16-Item-Classification
This project accurately classifies waste items using transfer learning and fine-tuning techniques. This project utilizes the waste item dataset for training and evaluation.
 
## Overview
This project downloads the dataset and splits it into the training and testing sets. The training set is used to train the model, and the testing set is used to evaluate the model. The model is then fine-tuned using the training set and evaluated using the testing set. This project uses early-stopping and model-checkpointing techniques to prevent overfitting and save the best model. The final model is then used to predict the class of the waste items.

## Results
The model predicts the class of the waste items with an accuracy of 80%. The model is saved as a .h5 file and can be used to predict the class of new waste items. The extracted features model predicted 'O' when the actual was 'O'.

## Installation
To get started, clone the repository and install the required dependencies:

In Docker and JupyterLab

```bash
git clone https://github.com/lucianoscarpaci/VGG16-Item-Classification.git
```

## License
This project is licensed under the MIT License.


# Fine-Tuning VGG19 on the CIFAR100 Dataset

## CIFAR100
<img width="1409" alt="Screenshot 2025-02-18 at 23 17 52" src="https://github.com/user-attachments/assets/96efe285-a547-4b16-b74e-c07102c84432" />  

## Model Overview - Similar to CIFAR10
<img width="909" alt="Screenshot 2025-02-18 at 23 23 49" src="https://github.com/user-attachments/assets/23eda74f-3915-41a8-9774-3b224e4823d0" />

## Description
This model uses [VGG19](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19) which is an already trained AI model on the
[Imagenet Dataset](https://www.image-net.org/challenges/LSVRC/index.php) as a base-model. It then trains the base-model - taking a number of layers - on the [CIFAR100 DATASET](https://www.cs.toronto.edu/~kriz/cifar.html) to make predictions on 100 classes from 10 superclasses.  

## Model Output
After training, the model obtained a validation accuracy of 53.3% (0.533) which indicates VGG19 might not be the perfect model for CIFAR100 after running 20 epochs.  
![output](https://github.com/user-attachments/assets/8635540c-5cdf-4265-b8b0-c9e69955b2a0)


## Usage
**Clone the Project**

To clone this repository, use the following command:

```bash
git clone https://github.com/Bibliophiles/Fine-Tuning_VGG19_on_CIFAR100.git
```

These instructions are for running this project in Google Colab after cloning the repository.

Open Google Colab: Go to https://colab.research.google.com/.

**Upload the Notebook:**

In Colab, click "File" -> "Upload notebook". Navigate to the cloned repository on your local machine and select the .ipynb file.  

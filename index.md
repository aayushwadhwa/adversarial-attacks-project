## Adversarial Attacks on Machine Learning Models

The project involves using gradient based methods to attack state-of-the-art imagenet models- ResNet, InceptionV3 and EfficientNet. We have checked and compare robustness of these models using FGSM, PGD and DeepFool attacks provided by attacking tools such as CleverHans, ART etc.

## Attack Methods
Three attack methods have been used to compare different tools on CV models. These are:
1. Fast Gradient Sign Method: Basic, fast and effective of all the gradient based method.
2. Projected Gradient Descent Method: Produces best results with minimum perturabations
3. DeepFool: Most accurate and effective attacking method

## Attacking Tools
Above methods were used with these attacking tools:
1. Cleverhans
2. Adversarial Robustness Toolbox
3. AdvBox
4. Foolbox

## Extension
There are two new attack methods that are added with this project.

#### DeepFool
Cleverhans has been extended with DeepFool attack method and the code can be found [here](https://github.com/aayushwadhwa/cleverhans/blob/master/cleverhans/tf2/attacks/deep_fool.py)

#### GAN for Adversarial Attacks
Generative networks were trained with adversarial images to construct more adversarial examples that will fool machine learning CV models. The code and results of the implementation can be found on [this Jupyter Notebook](https://github.com/aayushwadhwa/adversarial-attacks-project/blob/main/Attack%20GAN/Adversarial_Attack_with_DCGAN%20(1).ipynb) 


Please feel free to view the code in the [github repository](https://github.com/aayushwadhwa/adversarial-attacks-project), and raise a pull request to enhance the methods and the project.

The project was develop collective by Aayush Wadhwa and Aru Chahal for ECE653: Software Testing, Quality Assurance and Maintenance under the guidance of Prof. Vijay Ganesh.

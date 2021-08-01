# Implementation of Adversarial Attacking Tools

The project is a part of UW ECE653, Software Testing, Quality Assurance and Maintenance. It involves:

* Attacking state-of-the-art imagenet models with FDSM, PGD, and DeepFool methods
* Using modern attacking tools to generate attacks on these models
* Extending a tool with new attacking method

## Attacks Performed
* Fast Gradient Sign Method
* Post Gradient Descent
* DeepFool

## Tool Used
* [CleverHans](https://github.com/cleverhans-lab/cleverhans)
* [ART](https://github.com/Trusted-AI/adversarial-robustness-toolbox)
* [FoolBox](https://github.com/bethgelab/foolbox)
* [AdvBox](https://github.com/advboxes/AdvBox)
* [ARES](https://github.com/thu-ml/ares)

## New Attack Methods Implemented
* DeepFool Attack for CleverHans. Can be found [here](https://github.com/aayushwadhwa/cleverhans/blob/master/cleverhans/tf2/attacks/deep_fool.py)
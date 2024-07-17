# Training the Model

## Instructions

In this exercise you'll build Binary Classification models for 4 separate datasets each posing a unique challenge to explore. After building and training your model attempt to optimize your Model utilizing the skills we learned in class today.

## Data Sets

- Machine Failure
  - target value: `fail`
- Customer Purchase
  - target value: `Purchase Status`
- Titanic-Dataset
  - target value: `Survived`
  - Think about which features you need to make your model efficient... is there any data you have that your model shouldn't consider?
- Plant Growth
  - target value: `Growth_Milestone`
  - In this data sample we aren't just working with numbers... How would you turn these text inputs in your data into something your Model can work with?

## Tools

- [LabelEncoding](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)
- [leaky_relu](https://pytorch.org/docs/stable/generated/torch.nn.LeakyReLU.html)
- [Learning Rate Schedulers](https://pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.StepLR.html)

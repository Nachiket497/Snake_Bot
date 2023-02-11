# Snake_Bot
It's repository for the Snake-like Robot Modeling and Navigation (Project 224) of Mathworks


## Results: 


## Prequisite:

* Install Simscape multibody link plugin: [link](https://www.mathworks.com/products/simscape-multibody.html)

## Getting started:

* To get started, open the matlab terminal and execute the followint command:

```
open_system('TestModule.slx')
```

![image](https://user-images.githubusercontent.com/59257455/218241521-c4bb55df-5562-4043-af25-18e5c7117d78.png)


* To start the simulation click on the run button.

## Model Architecture and Conventions

* There are 6 links in our model.
* The singal link is repeated multiple time with orthogonal  change in axis of rotation.

![single link]{}

* Each link is indivudually actuated.

* The Actuation in the joints is sinusoidal with phase differece of 60&deg; and Angular frequency 15 rad/sec.

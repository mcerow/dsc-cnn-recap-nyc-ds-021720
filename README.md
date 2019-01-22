
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 43.

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:

* CNN are often preferred over densely connected networks when the goal is to perform image classification
* Using CNNs instead of densely connected networks can drastically decrease the amount of parameters needed (and as a consequence, increase the speed)
* When building a CNN, the end of the network architecture always connects back to a densely connected network to perform classification
* At the most basic level, a convolution is particularly good at detecting small image features, such as horizontal or vertical edges
* Convolutions use *filter* to detect these small patterns, and these filters are generally of size 3x3 or 5x5.
* In CNNs, padding can be used to prevent shrinkage and to make sure pixels at the edge of an image deserve the necessary attention
* To understand CNN structures and how the dimensions change in each layer, it is important to understand how filters work and how the number of filters affect the network structure.
* When visualizing intermediate layers in a CNN, you noticed that images become more abstract with each layer we add to a CNN

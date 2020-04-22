# CycleGANs
Project for CS 7180

Currently: Sample images with different RGB value with varying intensitites; transfering it to checker board design (in domain)


To-Add:
- tf model with gen_(x/y)/dis_(x/y)
- loss function implemented individually

Project is about GANs and CycleGANs in particular. 
Reproducing the results from the paper "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks" by Jun-Yan Zhu et al. The model converts an image from a particular domain to another domain. 

For example, Zebra - Horse, Apple - Orange, Satellite view - Map view, MNIST - color inverted MNIST, Summer Landscape - Winter Landscape. Some more applications: https://lnkd.in/eWBq7bX

The model is implemented using the Keras package. Although the computational resources were limited, the results are clear. More training would produce even better results.

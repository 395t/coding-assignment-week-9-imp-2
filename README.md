# coding-template

## Summary

### Description - GIRAFFE- Representing Scenes as Compositional Generative Neural Feature Fields

GIRAFFE is a learning-based rendering engine used to represent scenes as compositional generative Neural Features Fields. It is used for image synthesis. 
The main idea of implementing giraffe is that it incorporates a compositional 3D scene into the generative model to get more controlled image synthesis. 
Using this model the features of objects present in input image are extracted and added. Using this model one can achieve different scenes like rotating 
object, changing background, changing depth, changing horizontally. The Data set used in this is a local dataset with 1000s of images of cars. These input 
images are parsed through the generative model to create new images with unique and novel features. A compositional 3D scene is applied to generative model
to get the set of rotating images, change in depth and horizontal representation.

### Result

<img src="Output/rotation_cars.gif">

<img src="Output/tr_d_cars.gif">

<img src="Output/tr_h_cars.gif">
## Reference

Any code that you borrow or other reference should be properly cited.

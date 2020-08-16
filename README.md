# Neural-Algorithm-of-Artistic-Style
Neural style transfer (NST) is a very neat idea. NST builds on the key idea that,Following this concept, NST employs a pretrained convolution neural network (CNN) to transfer styles from a given image to another. This is done by defining a loss function that tries to minimise the differences between a content image, a style image and a generated image, which will be discussed in detail later. By the end of this tutorial you will be able to create very cool artwork like below.

![](https://github.com/Chromaniquej1/-Neural-Algorithm-of-Artistic-Style/blob/master/Images/paris_generated_at_iteration_4000.png)

## Why Neural Style Transfer
Deep neural networks have already surpassed human level performance in tasks such as object recognition and detection. However, deep networks were lagging far behind in tasks like generating artistic artefacts having high perceptual quality until recent times. Creating better quality art using machine learning techniques is imperative for reaching human-like capabilities, as well as opens up a new spectrum of possibilities. And with the advancement of computer hardware as well as the proliferation of deep learning, deep learning is right now being used to create art. For example, an AI generated art won’t be sold at an auction for a whopping $432,500.

## Architecture 
 The architecture of the model as well as how the loss is computed is shown below. You do not need to develop a profound understanding of what is going on in the image below, as you will be seeing each component in detail in the next several sections to come. The idea is to give a high level understanding of the workflow taking place during style transfer.
 
 ![](https://miro.medium.com/max/647/1*ZgW520SZr1QkGoFd3xqYMw.jpeg)
 
 ## How to download VGG16 pretrained model

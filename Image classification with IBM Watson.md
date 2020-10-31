# Image classification with IBM Watson

**label / keyword:** describes the images

**confidence score:** how confident the label describes the image (0 - 1)

- don't need to add up to 1 across all labels
- higher confidence score => more confident the model "believes" it has identified a particular label
- confidence score of "1.0" != 2 * a confidence score of "0.5" (more likely, not twice likely)
- labels with confidence score < 5 don't show up by default
- breadth vs. depth

**visual recognition**

- prepare image => analyze images
- prepare training data => train and create new models => analyze images

**train custom classifier**

- declare the labels / classes you want your custom classifier to recognize
- gather numerous positive examples (minimum 10)
- training
- test with test set (set of images not used to train the classifier)

![image-20201031002240338](C:\Users\maggi\AppData\Roaming\Typora\typora-user-images\image-20201031002240338.png)


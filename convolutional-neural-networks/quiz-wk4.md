## Special applications: Face recognition & Neural style transfer

###### 1. Face verification requires comparing a new picture against one person’s face, whereas face recognition requires comparing a new picture against K person’s faces.
- 

###### 2. Why do we learn a function *d(img1, img2)* for face verification? (Select all that apply.)
-

###### 3. In order to train the parameters of a face recognition system, it would be reasonable to use a training set comprising 100,000 pictures of 100,000 different persons.
- 

###### 4. Which of the following is a correct definition of the triplet loss? Consider that \alpha > 0α>0. (We encourage you to figure out the answer from first principles, rather than just refer to the lecture.)
- 

###### 5. When training one of the object detection systems described in lecture, you need a training set that contains many pictures of the object(s) you wish to detect. However, bounding boxes do not need to be provided in the training set, since the algorithm can learn to detect the objects by itself.
- False

###### 6. Suppose you are applying a sliding windows classifier (non-convolutional implementation). Increasing the stride would tend to increase accuracy, but decrease computational cost.
- False

###### 7. In the YOLO algorithm, at training time, only one cell <html>&mdash;</html> the one containing the center/midpoint of an object <html>&mdash;</html> is responsible for detecting this object.
- True

###### 8. What is the IoU between these two boxes? The upper-left box is 2x2, and the lower-right box is 2x3. The overlapping region is 1x1.
![Image of Boxes](/convolutional-neural-networks/images/iou.png)
- 1/9

###### 9. Suppose you run non-max suppression on the predicted boxes above. The parameters you use for non-max suppression are that boxes with probability ≤ 0.4 are discarded, and the IoU threshold for deciding if two boxes overlap is 0.5. How many boxes will remain after non-max suppression?
![Image of Predicted Boxes](/convolutional-neural-networks/images/boxes.png)
- 5

###### 10. Suppose you are using YOLO on a 19x19 grid, on a detection problem with 20 classes, and with 5 anchor boxes. During training, for each image you will need to construct an output volume *y* as the target value for the neural network; this corresponds to the last layer of the neural network. (*y* may include some “?”, or “don’t cares”). What is the dimension of this output volume?
- 19x19x(5x25)

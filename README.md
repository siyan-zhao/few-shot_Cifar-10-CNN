# Cifar-100-Loading
Returns all the training images and labels for 5 classes, selected at random. 

a) loads in the Cifar 100 dataset

b) Has one method: get_new_data. This method returns all the training images and labels for 5 classes, selected at random. The labels are changed into one_hot variables out of only 5 classes, not 100, since you we're only sampling 5 classes at a time. 

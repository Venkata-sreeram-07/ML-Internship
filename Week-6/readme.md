## This was Week-6 Assignment
> In this assignment, you need to do transfer learning on CIFAR100 dataset.
> You have to use the Resnet pretrained model for this assignment. (Any version of RESNET is fine)
> You need to do all the things that we saw in the video, like
 Loading the pretrained resnet model <br>
Freezing the layers <br>
Modifying the output layer <br>
Hyperparameter tuning <br>
Training <br>
Train on GPU <br>
Make sure you clear the GPU cache and delete variables after every step in training <br>
Make use of TRAIN mode and EVAL mode to turn BatchNorm and Dropout "ON" and "OFF" <br>
Implement model checkpointing to save your best model <br>
Make sure you download the model weights into your local machine after training <br>
After training, load the best model weights and extract a batch of images from the test_loader <br>
Generate the predictions of your best model on the test batch that you extracted and print out the class names of the prediction along with the actual class labels of those images <br>
Finally, print out the train and test accuracies of your best model. <br>

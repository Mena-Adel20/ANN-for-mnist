# 1-Data Exploration and preparation:
<ul>
<li> Load the dataset and perform initial data exploration.</li>
<li> Begin by familiarizing yourself with the dataset.</li>
<li> Identify the number of unique classes.</li>
<li> Identify the number of features.</li>
<li> Check for missing values.</li>
<li>Normalize each image by dividing each pixel by 255.</li>
<li> Resize images to dimensions of 28 by 28. After resizing, visualize some images to verify the correctness of the reshaping process.</li>
<li>Split the training data (mnist_train) into training and validation sets.</li>
</ul>


# 2- Experiments and results:

## Initial Experiment: 
Implement the K-NN algorithm for classificationand utilize a grid search technique to determine the optimal hyperparameters.
## Subsequent Experiment:
Construct and train two different architectures of Artificial Neural Network (ANN) for classification, exploring variations in the number of hidden neurons, learning rate,and batch size.

<li>Compare the outcomes of the first and second experiments, discerning which approach yields the highest accuracy on the validation dataset.</li>
• Get the confusion matrix of the best model.
• Save the best model, then reload it in a separate file, and use it on the 
testing data loaded from mnist_test.csv.

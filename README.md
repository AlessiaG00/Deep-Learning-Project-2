# Deep-Learning-Project-2

This Deep Learning project focuses on image classification. The project was conducted in collaboration with 2 university colleagues.

The dataset used comprises 31,807 images (48 x 48) of faces of individuals. Facial expressions have allowed us to categorize the images into 6 categories: Angry, Fear, Happy, Neutral, Sad, Surprise.

To achieve our goal, we decided to explore various neural network models. As evident from the project, in order to find the most effective model, we made several attempts, starting with the well-known AlexNet model, which proved to be the most suitable for our purpose among known models. Additionally, we applied transformations to the images in the training set to prevent overfitting issues and assist the model in learning more robust features.
Hyperparameters were adjusted in each attempt. 
For performance metrics, we used the cross-entropy loss function and accuracy.

The model that achieved better performance was an AlexNet model to which batch normalization layers were added to normalize data and accelerate the convergence of the deep neural network. We also employed a regularization technique, namely weight decay. 
Despite the loss function value not being particularly optimal, this model had the smallest gap between train accuracy and test accuracy.

The obtained test accuracy is 53%, which may not be very high, but we were aware that this type of project is complex, and even in academic literature, slightly better results (around 70%) have been achieved.


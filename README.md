# Transfer-learning-project

This project implemented neural style transfer by using transfer learning (VGG19 and Resnet50) to extract content and style representations and define gradient descent of total loss to update random images until matching content and style features
• Improved algorithm by testing on different weighted loss function of content & style loss (L1 and L2 regularization, adding concepts of variation loss, generating random initial images, increasing content layers and adjusting learning rate
• Tested on three content images and two style images and achieved convergence in content and style loss function to 0.1 with L2 regularization, ratio of content and style loss as 100, variation loss as 10 and learning rate as 15

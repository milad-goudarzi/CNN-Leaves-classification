# ANN-DL
"RN with more neurons" is the submitted model.
In this model I used ResNet for Feature Extraction and two hidden Layers with 512 neurons with relu activation function and a dropout layer between each of them with rate = 0.3. Moreover, I put a global average pooling layer after feature extraction part and also used softmax as activation function of output layer of the model.
I trained the model two times. Because I used transfer learning. First time with setting the pre-trained network to be non-trainable and second time with setting last 32 layers of the pre-trained network to be trainable. Additionaly, I used a low learning rate, since the initial weights came from ImageNet and are already good weights for our problem.

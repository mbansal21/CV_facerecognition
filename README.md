we use a pre-trained model trained on Face recognition to recognize similar faces.Here, we are particularlyinterested in recognizing whether two given faces are of the same person or not.


I applied the pre-trained VGG face model and weights and loaded all the images embeddings.Then performed PCA for dimesionality reduction from 2622 to 128.
● Build an SVM classifier to map each image to its right person and predict their faces using SVM model.I am able to achieve 96 % accuracy.

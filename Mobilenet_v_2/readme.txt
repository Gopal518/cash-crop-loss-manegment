I have mentioned the file name and what does it contain, for better understanding
Dataset : folder contain a processed image (applied filter to enhance the image)
model_training.ipynb : code for processing images, training and teasing the images
Consfussion_matrix : result on testing dataset getting ~95% accuracy
labelled_image_data.csv: contains the label of the image used while training
log_training-xxxxx.csv : CSV file created my logger to track the model performance
E[]_loss[]_acc[].h5 : weight file, saved using callback on every improvement
accuracy_loss_curve.png : measures our model error.
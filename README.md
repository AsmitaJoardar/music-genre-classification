# music-genre-classification
Music Genre Classification (MGC) using the GTZAN dataset through machine learning and deep learning techniques.

The files named Part1.ipynb, Part2.ipynb, Part3.ipynb and Part4.ipynb must be run in this exact order before the other files because the outputs of these codes are the inputs to the other codes.

In Part5.ipynb and Part7.ipynb the codes under the headings 'Plot the Training & Validation Curve' may need to be changed depending on the output of the codes under the 'Train the Model' headings. Our code works for the output where the variable names are 'loss' and 'val_loss'. These variable names are assigned automatically and if they change when running the codes, relevant changes need to be made in lines 2 and 3 of the codes under the 'Plot the Training & Validation Curve' headings.

Part1 through Part4 contain the data pre-processing codes. Part5 implements MGC through a LSTM model. Part6 implements a Neural Network model. Part7 shows MGC using a Transfer Learning Model which is based on the VGG16 model. Finally, Part8 performs MGC using various machine learning classifiers.

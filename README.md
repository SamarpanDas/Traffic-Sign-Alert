# Traffic-Sign-Alert-
Under Developmental stage

Link to download the actual dataset : https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

The Training set was ideal to use, it had subfolders 0 - 42 (which means a total of 43 classes) containing images for its respective class.

The Test set had 12,000 images(approx) randomly arranged with a "test.csv" file attached which had 8 columns among which there was a column conatining the imagePath and its corresponding classId.

I found the original test data set uncomfortable to use, thus I wrote the "Support for Traffic (Initial Test set file Handling).ipynb" file which created a Testset folder and subsequently created 43 subfolders(named from 0 - 42) inside it. 
Then the following lines of code picked up images from the original Test Set and put those images in the various subfolders in the newly created Test Set as per their classId mentioned in the test.csv file.


Therefore the original training set and the newly created test set were used to train and evaluate the Model which is present in the TrafficMain.ipynb file.
The train and test set used now resembled the same format.     
                            
                            
                            
              Train/Test set ---> 43 subfolders (named from 0 - 42 ; referring to the 43 classes) ---> containing their respective images.


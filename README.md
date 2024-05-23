This project is coded and compiled by using Google Colab.
1. First, we need to define the folder where the processed images will be saved in Part 1: Process and Save. Then, select an image as the input for processing and saving in Part 1. Finally, run the Part 1 code to compile, generate, and save the ROI images into the specified folder.
2. After inputting the iris image and running the first part (Process and Save), we can change the folder path in Part 2 for matching with the path in previous Part. Then, enter the path of the iris image into the main function of Part 2 (Recognition) for checking with the previous iris (which is processed and saved in the first part) and run the Part 2.
3. About the result of this code:
   + For the Part 1, it will process the input image and save the ROIs images into the provided folder for checking in the next Part.
   + For the result of Part 2, it will process the second input image, get the ROIs image for comparing with the ROIs from the saved folder. Then, it calculates the similarity score between 2 input iris images, compares the score with threshold and shows the result (ACCEPTED or DENIED)

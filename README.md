# Mathematics_answer_sheet_checking_system
## Step 1 - Equations Recognization
This part was really hard. The firts part is to read the **equations line by line** and then number them accordingly. For this we need a best recognition model to work on. For this I chose **MASK-RCNN**. This choice provided me with **100% results** for the object detection on the sheets and this model recognized each equation seperately. Worked on all the 26 sheets and then got results.
## Sheet1
![Sheet1](https://github.com/mayank2705/Mathematics_answer_sheet_checking_system/blob/main/download.png)

## Step 2 - To seperate the equations and then treat them accordingly
This part includes the process only to just seperate the list of the images simultaneously and then store them seperately.
**Line1**
![Line1](https://github.com/mayank2705/Mathematics_answer_sheet_checking_system/blob/main/Line1.JPG)

**Line2**
![Line2](https://github.com/mayank2705/Mathematics_answer_sheet_checking_system/blob/main/Line2.JPG)

**Line3**
![Line3](https://github.com/mayank2705/Mathematics_answer_sheet_checking_system/blob/main/Line3.JPG)

## Step 3 - Recognize all the letters and symbols in the equations
For this I used thresholding and then seperated each letter and symbol using contours and then seperated them and stored them as well. We can look in the notebook for the results.

## Step 4 - Classification of those symbols and letters
For this step I used a neural network which classifies the symbol image in the form of MNIST and predicts the symbols and store them in the list of lists that is nested lists. These lists are in the accordance to the equations written in the sheets.

## ** Currently working **



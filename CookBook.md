a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md.


**The main fuction** main(). Simple and clear. It runs the show, it knows where the dataset resides and it works with the other defined functions to get the job(s) done. I'm doing to take the comment right out of the code to describe the transforamtion.

<ol>
<li>Load and join the Y test and train together</li>
<li>Combine the Y train and test and row bind subjects together</li>
<li>Combine the x_train and x_test data and apply the headers ( Here we narrow the data set going after the columns that only contain mean and std) </li>
<li>Combine the all the data together</li>
<li>clean up the column heading names</li>
<li>record teh data to file</li>
<li>
</ol>

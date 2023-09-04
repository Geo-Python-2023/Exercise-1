# Exercise 1: Cooking up some Python

In the “Taste of Python” lesson this week we have learned a few basic things in Python. Now you get your chance to demonstrate your skills.

This exercise is inspired by [Finland being ranked the world's happiest country for the 6th year in a row](https://yle.fi/a/74-20023112). As the instructors of the Geo-Python course, we think we've found a better way to assess the individual happiness of people in Finland (particularly those taking this course!), and we're going to test our idea with you. In *five easy steps (or problems)* we'll be able to reveal your happiness based on two of life's most important happiness factors: Ice cream and sleep!

## Problem 0 - Filling out the pre-course survey

Before you get started with the exercise, we ask that you **please fill out the Geo-Python/AutoGIS pre-course survey at https://elomake.helsinki.fi/lomakkeet/125237/lomake.html**. Your responses will help shape how we teach this autumn!

## Problem 1 - Creating your own Jupyter notebook

1. Open Jupyter lab from the [Exercise 1 landing page](https://geo-python-site.readthedocs.io/en/latest/lessons/L1/exercise-1.html#part-3-cooking-up-some-python) on the course site and create a new notebook.

2. Use the file browser on the left side of the Jupyter Lab window to change the name of your notebook file to `Exercise-1.ipynb`.

## Problem 2 - Defining some numerical variables

In the top cell of the new notebook:

1. Create a variable called `ice_cream_rating` and use it to store an integer value (whole number) between 0 and 10 that reflects your general opinion about how much you enjoy eating ice cream.

2. Create another variable called `sleeping_rating` and use it to store another integer between 0 and 10 that reflects your opinion about how much you enjoy sleeping.

3. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 3 - Defining some character string variables

In the new cell that appears:

1. Store your first name as a character string in a variable called `first_name`.

2. Store your last name as a character string in a variable called `last_name`.

3. (*Optional*) Define a third variable called `my_name` that will combine your first and last names into a single character string with a space between the names.

4. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 4 - A bit of math

In order to assess your overall happiness it is necessary to combine the ice cream and sleeping ratings. To do this:

1. Calculate the average of your `ice_cream_rating` and `sleeping_rating` variables and store the resulting value in a variable called `happiness_rating`.

2. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 5 - Checking data types

The next step is to investigate the kinds of data we're working with. In another Python cell:

1. Use a built-in Python function to check the data types of the `ice_cream_rating`, `first_name`, and `happiness_rating` variables. In order to see the data types for more than one variable in a single Python cell, you will need to print out these values using another built-in Python function.

2. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

3. Did all of the data types make sense? Were there any data types that were different than you expected? In the new Python cell that appeared after running the code above, type in your responses to these questions.

4. For the cell containing your answers to the questions above, change the kind of cell from **Code** to **Markdown**.

5. Run the Markdown cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 6 - Displaying text on the screen

Finally, you can use your Python skills to generate output on the screen similar to that below. Use one command to generate each line of output.

```
My name is Dave and I give eating ice cream a score of 9 out of 10!
I am Dave Whipp and my sleeping enjoyment rating is 8 / 10!
Based on the factors above, my happiness rating is 8.5 out of 10, or 85.0 %!
```

Note that your code should replace “Dave” with the contents of your `first_name` variable, “9” with your value stored in the variable `ice_cream_rating`, etc. For your equivalent text with the full name (e.g., "Dave Whipp"), you can either use the values from the variables `first_name` and `last_name`, or the value in variable `my_name`.

## Finishing the exercise

To complete this exercise, download your notebook to your computer and upload it to GitHub in your **own** Exercise 1 repository that you created using the GitHub Classroom link.

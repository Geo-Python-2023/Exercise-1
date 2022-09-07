_Dear students! Please also fill in the **Geo-Python/AutoGIS pre-course survey: https://elomake.helsinki.fi/lomakkeet/119154/lomake.html**.  Your responses will help shape how we teach this fall._

# Exercise 1: Cooking up some Python

In the “Taste of Python” lesson this week we have learned a few basic things in Python. Now you get your chance to demonstrate your skills.

This exercise is inspired by an analysis that determined [Finland is the world's happiest country](https://www.weforum.org/agenda/2019/03/finland-is-the-world-s-happiest-country-again/). As the instructors of the Geo-Python course, we think we've found a better way to assess the individual happiness of people in Finland (particularly those taking this course!), and we're going to test our idea with you. In *five easy steps (or problems)* we'll be able to reveal your happiness based on two of life's most important happiness factors: Ice cream and sleep!

## Problem 0 - Creating your own Jupyter notebook

Open Jupyter lab from the [Exercise 1 landing page](https://geo-python-site.readthedocs.io/en/latest/lessons/L1/exercise-1.html#part-3-cooking-up-some-python) on the course site, and create a new notebook.

## Problem 1 - Defining some variables

In the top cell of the new notebook:

1. Create a variable called `ice_cream_rating` and use it to store an integer value (whole number) between 0 and 10 that reflects your general opinion about how much you enjoy eating ice cream.

2. Create another variable called `sleeping_rating` and use it to store another integer between 0 and 10 that reflects your opinion about how much you enjoy sleeping.

3. Run the cell by pressing **Shift-Enter**.

## Problem 2 - Reading in variable values

In the new cell that appears:

1. Use the `input()` function to prompt the user to enter their first name and store it in a variable called `first_name`.

2. Use the `input()` function again to prompt the user to enter their last name and store it in a variable called `last_name`.

3. (*Optional*) Define a third variable called `my_name` that will combine the user's first and last names into a single character string with a space between the names.

4. Run the cell and enter the requested information at the prompts.

## Problem 3 - A bit of math

In order to assess happiness it is necessary to combine the ice cream and sleeping ratings. To do this:

1. Calculate the average of your `ice_cream_rating` and `sleeping_rating` variables and store the resulting value in a variable called `happiness_rating`.

2. Run the cell by pressing **Shift-Enter**.

## Problem 4 - Checking data types

The next step is to investigate the kinds of data we're working with. In another Python cell:

1. Use a built-in Python function to check the data types of the `ice_cream_rating`, `first_name`, and `happiness_rating` variables. In order to see the data types for more than one variable in a single Python cell, you will need to print out these values using another built-in Python function.

2. Run the cell by pressing **Shift-Enter**.

3. Did all of the data types make sense? Were there any data types that were different than you expected? In the new Python cell that appeared after running the code above, enter your responses to the questions above.

4. For the cell containing your answers to the questions above, change the kind of cell from **Code** to **Markdown**.

5. Run the Markdown cell by pressing **Shift-Enter**.

## Problem 5 - Displaying text on the screen

Finally, you can use your Python skills to generate output on the screen similar to that below. Use one command to generate each line of output.

```
My name is Dave and I give eating ice cream a score of 9 out of 10!
I am Dave Whipp and my sleeping enjoyment rating is 8 / 10!
Based on the factors above, my happiness rating is 8.5 out of 10, or 85.0 %!
```

Note that your code should replace “Dave” with the contents of your `first_name` variable, “9” with your value stored in the variable `ice_cream_rating`, etc. For your equivalent text with the full name (e.g., "Dave Whipp"), you can either use the values from the variables `first_name` and `last_name`, or the value in variable `my_name`.

## Finishing the exercise

To complete this exercise, upload your changes to GitHub in your **own** Exercise 1 repository that you created using the GitHub Classroom link.

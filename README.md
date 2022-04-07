# 03 - Assignment 1

In this assignment,  we will focus on learning some best practices on the typical PyData libraries: Jupyter/IPython, Pandas, Numpy, Scikit-learn, Matplotlib.

Exercises

1. Create a notebook and go through the chapter on housing price prediction. You have been working on a modified version of this particular problem in the previous modules and should already have an idea of the DS problem being solved. Now is the time to dive deep and understand the details of the modeling and processing steps.


2. Try the exercises provided in the chapter on housing price prediction. Try to solve it yourself before referring to the solutions provided in GitHub (https://github.com/ageron/handson-ml2). 

    Add the final notebook (all cells executed and displayed) for Exercises 1 and 2 and raise a PR.


    The chapter on housing price prediction uses a scikit learn pipeline and custom transformers to simplify and robustify the modeling code. A more detailed exposition of the scikit-learn pipeline API and using it for preprocessing/feature-generation can be found in the third reference (see reading material section above). Create a PR and submit it.

3. Refactor your ML code to use sklearn pipeline. Create a custom transformer for the new features (i.e. rooms_per_household, bedrooms_per_room, population_per_household) generated in your code. After Exercises 1 and 2, you should already have helper code for this. Push a PR and discuss your implementation with the course facilitator.

    NOTE: When applying a ColumnTransformer on a Pandas dataframe, the transformed dataset is a Numpy array. If you want to recover the column names, here is an example code snippet that can be useful.

Deliverables
- Notebook(s) for exercises 1 and 2.

- PR link for Exercise 3.

NOTE: Follow the usual process and standards for creating a PR (create an issue, name the branch appropriately, link the issue,  add a meaningful title and description).
# Linear Regression
The contents of this project are heavily inspired by the machine learning course presented at Stanford by Andrew Ng. But using Python instead.
I used the NumPy library to work with N-dimensional arrays and matplotlib for plotting. Also, for visualizing the cost function in 3D and contour plots.

In part 1, the goal is to implement linear regression with one variable to predict profits for a food truck. The file trucks.txt contains the dataset for our linear regression problem. The first column is the population of a city and the second column is the profit of a food truck in that city. Machine should use this data to help select which city to expand to next. I used Mean Square Error as a cost function. NumPy library was used to work with N-dimensional arrays. Matplotlib was used to plot graphs and visualize the cost function in 3D and contour plots..

In part 2, I implemented linear regression with multiple variables to predict the prices of houses. Suppose I am selling my home and want to know what a good market price would be. One way to do this is first to collect information on recent houses sold and make a model of housing prices. The file houses.txt contains a training set of housing prices in Portland, Oregon. The first column is the size of the house (in square feet), the second column is the number of bedrooms, and the third column is the price of the house. First, I did feature normalization since house sizes are about 1000 times the number of bedrooms. Then gradient descent algorithm was run (cost function = MSE), and in the end, multiple learning rate values were tried out to find a learning rate that \\converges quickly 

In Part 3,  I predict the house price using a Normal Equation, a closed-form solution to linear regression which does not require any feature scaling, and you will get an exact answer in one calculation.




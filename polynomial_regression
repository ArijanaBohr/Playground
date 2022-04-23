import numpy
from sklearn.metrics import r2_score

#Create the arrays that represent the values of the x and y axis:
x = [1,2,3,5,6,7,8,9,10,12,13,14,15,16,18,19,21,22]
y = [100,90,80,60,60,55,60,65,70,70,75,76,78,79,90,99,99,100]

mymodel = numpy.poly1d(numpy.polyfit(x, y, 3)) #NumPy has a method that lets us make a polynomial model:

speed = mymodel(17) #predict for x = 17
print(speed)

#you can run this code directly in the terminal
#https://www.w3schools.com/python/python_ml_polynomial_regression.asp

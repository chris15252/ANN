# An important note 

The analyses of the underlying ANN models in this paper were written prior to any successful attempts at predicting peformance indicators. However, the program and data were reevaluated to remove any erroneous data or programmatic errors in an effort to realize the initial objective of the study. I was successful in correcting the issues and able to significantly reduce the MSE observed for each of the ANN models. The paper has not been revised as of yet, but the plan is to rewrite it to include the new information from the successful tests.

# Abstract

### Purpose

The purpose of this study is to make
predictions about some performance indicators of a
turbofan aircraft by utilizing modern Artificial Neural
Network (ANN) models.

The problem of determining optimum performance in
today’s modern turbofan aircraft is a very old
problem with real test data to back up calculated
predictions. Being a very old industry, aerospace has
been slow to adopt the use of Artificial Neural
Networks to predict the performance of new engine
designs. However, with modern ANN models the
real-world test data can be utilized to predict engine
and aircraft performance with a high degree of
precision. By using an ANN to predict performance,
time spent calculating the impact of design changes
can be reduced.

### Objective

This study is intended to complement the
presentation that analyzed other studies that
attempted to use ANN models to predict performance
indicators of an aircraft based on a few measured
inputs. The goal will be to expand upon the work by
attempting to perform the same predictions using a
simple ANN model, the Levenberg-Marquardt (LM)
and Bayesian regularization (BR) algorithms, as well
as the ReLU activation function. This will be
accomplished by creating the ANN in Python along
with utilizing PyTorch.

The inputs that will be used to train and test the
model will be:

• Airspeed

• Altitude

• Air Temperature

• Exhaust Temperature

• Cruise Mach Number

The expected outputs will be:

• Thrust

• Ground Speed

• Fuel Consumption

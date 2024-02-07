# Unit converter

Converts between units.


## Background

There is a scientific calculator app that performs proper dimensional analysis with high precision values. 

The author thought "unit conversions is just a graph problem. An easy graph problem. I want a graph problem to solve". And here is at least the start if not completed app.

4 'mph' = 3 'm'

You express the units you wish to be convertable as equivalent expressions.

It will reduce the expression in terms that you express.

All units are variables under the hood. Solving for certain variables or simplifying expressions are done via conversions. All numbers are expressed as rational numbers as much as possible and then converted to floating point only when necessary. rational numbers are also reduced if possible. rational numbers greater then 64bit for either numerator or denomenator, the calculation may either error or be incorrect. Any calculation that must be calculated using floating point may have an error due to floating point calculations.



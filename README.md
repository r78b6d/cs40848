java c
Introduction to Java CS9053 Section I2
Friday, October 11, 2024
Due: Saturday, October 19, 2024 11:59pm
Part I
A polynomial is given by:

In part I, create fill out the Polynomial class using a constructors that will take a String or Array of Doubles as input representing the coefficients an,…a0, and implement the mult method, which takes another Polynomial and returns a new Polynomial object representing the product of the two Polynomial objects.
Then implement y, taking a value of x and returning the result of the polynomial
Finally, implement toString such that the polynomial with coefficients 5, 4, 3 has the output:
3x^2 + 4x + 5
(assuming you choose to say that the ith index of the ArrayList represents ai)
I’ve implemented this with an ArrayList field but you can do it however you like with the coefficients in whatever order you like.
Part II
We have a file employeelist.txt. This contains a list of employees and their associated classes. You can see that the concrete subclasses of Employee are HourlyEmployee, SalariedEmployee, and Manager. Each Employee object has a Manager represented by the id value, except for Employee 0, whose manager is -1. An abstract method called ca代 写Introduction to Java CS9053 Section I2Java
代做程序编程语言culateAnnualSalary calculates the annual salary for that Employee, which will be different depending on the nature of how they are paid.
SalariedEmployees have a weekly salary. HourlyEmployees have an hourly rate and a number of hours scheduled per week. Managers have a weekly salary and a maximum bonus (a 10% bonus having the value of 0.1).
In the file CalculateYearlyPayroll.java,  in the file employeelist.txt, using the split method for each like you read in to split the comma-separated values and create the appropriate Employee object in parseEmployee. parseEmployee should throw an UNCHECKED EmployeeTypeException with a useful  Exception message if the Employee subclass is one that doesn’t currently exist.
Put each Employee object in the ArrayList allEmployees, which should not be able to accept any objects other than Employee objects.
Finally, calculate the min and max payroll for the year, assuming 52 weeks in the year and the possibility that all bonuses could be 0% to the maximum possible bonus. This also means that you may want to add other methods and so on to make the min and the max possible salary of a Manager easy to calculate.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

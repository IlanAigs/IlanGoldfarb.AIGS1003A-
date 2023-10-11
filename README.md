# IlanGoldfarb.AIGS1003A-
AIGS1003A Assignment 1

"""
Question 1
Bayes’ theorem:
P(x|y) = ( P(y|x) * P(x) ) / P(y)    

In our case:
    1. The Naive Bayes’ assumption is that every variable is conditionally independent:

P(sunny|"a cone of ice cream") = (P("a cone of ice cream"|sunny) * P(sunny) ) 
                                        / P("a cone of ice cream")
    
P(sunny|"a cone of ice cream") = (P(a|sunny)( P(cone|sunny)( P(of|sunny)( P(ice|sunny)( P(cream|sunny)( P(sunny)
                                                        /P("a cone of ice cream")
                                                                                                       
    2. The same goes for our second case:
P(rainy|"a hot cop of coffee") = (P("a cop of coffee"|rainy) * P(rainy) )
                                        / P("a cop of coffee")  
                                                                                                       
P(rainy|"a hot cop of coffee") = (P(a|rainy)( P(hot|rainy)( P(cup|rainy)( P(of|rainy)( P(coffee|rainy)( P(rainy)
                                                        /P("a hot cop of coffee")    


The probability of both events occurring under the Naive Bayes assumptions is equal. 
This is because the probability of occurrence of each data point in the data set is equal, 
and thus the result of our equation is equal.



Sources:

I spoke with Mr. Rohit Lovers from AIGS 1003 Machine Learning class, Loyalist College, we tried to understand the python program together. (2023, Oct 7).


References:

Babatunde, Giwa, PhD, loss_activation, [PowerPoint Slides], Loyalist College.https://loyalistcollege.instructure.com/courses/8383/pages/naives-bayes?module_item_id=453519

Wikipedia. (2023, October 6) Bayes’ theorem. In Wikipedia. https://en.wikipedia.org/wiki/Bayes%27_theorem

"""

                      
                      
                      ------------:----Explanation----------------
            
            For first test case of sample input:

build temple in city 1 for 2 dollars.
repair road between 1 and 2 and repair road between 2 and 3 for total cost of 1+1 dollars. 
hence total cost is 4 dollars.
For second test case: You can build a temple in every city for a total cost of 6*2 = 12 dollars.

                         -----------****HINT 2 ***----------------

You can either make a road or temple if cost of road is greater then temple then it is easy to make
temple rather than road but if roat cost is less then temple then you need to find where temple can
 be make and how many different cities are connected to it
 for example:-
  1 2
  2 3
  3 4
  5 6
  temple cost is = 5 and road cost is = 2...
  so you can make temple in city 1 and city have path to city 1 are 2,3, and 4 so
  cost= 5 + 2 * 3 = 11
  also you have to make temple at city 5 as no path btwn city 1 and 5 but city 6 is connect to 5
  so cost = 5 + 2=7
  total = 11 + 7=18;
  basically you have to find component of graph....
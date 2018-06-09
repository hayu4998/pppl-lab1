# Lab 1 Write up

Hao Yuan

## FeedBack

## 2. Scala Basic: Binding and Scope 

(a) pi at line four is bound by the line 3,
 because line 3 is the in the scope of line 4.
 Pi at line 7 is bound by the line 1, because there
 isn't any pi that was declared within the function. So
 the value of pi is used by declaration outside the scope of 
 this function, which is line 1.
 
(b)The use of x at line 3 is directly bound by line 13, 
because line 13 called function f with value 
of x. Further more, line 13 is bound by line 1, which is under the same scope.The use of x at
line 6 is bound by x at line 3, which is a use site.
The use of line 10 is bound by line 3 as well, which is a
use site. The use of line x at line 13 is bound by line 1 since
it is in the scope of line 1.

## 3.scala Basics: Type

It is well-typed. Since the condition statement include outputs for both
true and false cases, the body can always have outputs. Since both 
output (b,1) and (b,a+1) have same return type ((int,int),int), the output
format is consistent. As a result, the body is well-typed.

The valid return type is ((int,int),int).

    $(b,a):((int,int),int) because:
        a : int because:    //a  is assigned to 1
            1:int       
        b : (int,int) because:  // b is assigned to (x,3)
            x:int
            3:int
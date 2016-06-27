### Review

1)What is the output of this function 

def h(){"Hello"}


2)
Which of the following is valid import and why 

import fruits.{apple => Mac, _}
import fruits.{apple => _, .}
import fruits.{apple => SQl}
import fruits.{apple => _,_}


3)
What is my output

val a =(12 -> "2")

a match {
case(12, x:String) => 12+x
case _             => 34
}

options

a)34
b)12
c)1234
d)14
e)122
f)None


4) output of this for comprehension

for(i <- 1 to 3; j <- 1 to 3; if(i!=j)) println(5* i+j+"")


5) What is the result type of a.flatten and a.flatmap

val a =List(List("A"),List("B"))

scala> a.flatten

scala> a.flatMap{x => x }


6)  What is the output of this operation List(1)::List(2,3)

a) List(1,2,3)

b) List(2,3,1)

c) List(List(1), 2, 3)                                                                                                                                                                                                                                                                                                                                                                                                                                            


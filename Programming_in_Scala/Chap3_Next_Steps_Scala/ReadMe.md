
Scala Basic points

->  scala code can be written in both imperative and functional style

->  vals cannot be reassigned but vars can be 

->  In functional style vals are prefered more over vars

->  As in java, scala also create a blueprint for objects with classes. 

->  Classes are instantiated with 'New' keyword

->  Arrays in scala are accessed by placing the index inside parenthesis 

     Ex:- greetStrings(0) = "Hello"
          greetStrings(1) = ", "
          greetStrings(2) = "world" 

->  if a method takes only one parameter, you can call it without a dot or parenthesses

     Ex:-  for (i <- 1 to 10)


->  There are no operators in scala. +, -, * etc are method calls on object

->  Therefore scala doesnot technically have operator overloading

->  When a variable is invoked by passing arguments scala internally invokes its apply method. For example accessing elements of an array

->  when an assignment is made to a variable to which parentheses and a single argument have been applied, the compiler will transform that into an invocation 
    of an update method that takes two parameters
 
     Ex :- greetStrings(0) = "Hello"
               
            will be transformed into
 
           greetStrings.update(0, "Hello")

->  Arrays are mutable objects

->  The method ::: in list prepends a list to another list

      Ex:- val oneTwo          = List(1, 2)
           val threeFour       = List(3, 4)
           val oneTwoThreeFour = oneTwo ::: threeFour
        
           oneTwoThreeFour(1, 2, 3, 4)

 ->  :: method (known as cons) prepends an element to the list

      Ex:- val oneTwo     = List(1, 2)
           val zeroOneTwo = 0 :: oneTwo

           zeroOneTwo(0, 1, 2)

->  If the method name ends in a colon, then the method is invoked on the right hand operand. For example, in 
    a ::: b, the ::: method is invoked on a, passing in b, like this: b.:::(a). Thus, b prepends 
    a to itself and returns the result

->  'Nil' is an empty List

->  Tuples can contain different types of elements

->  Difference between java interfaces and traits is that in java all methods in a interface is abstract whereas scala traits can have method with real code

->  java interface 'implements' scala traits 'extends'

->  Trait can extend zero to many traits

->  traits can be mix in at instantiation time using 'with' keyword


### Review

**1)What is the output of this function**

      def h(){"Hello"}


**2)Which of the following is valid import and why**
      
      a) import fruits.{apple => Mac, _}
      
      b) import fruits.{apple => _, .}
      
      c) import fruits.{apple => SQl}
      
      d) import fruits.{apple => _,_}


**3)What is my output**

  **val a =(12 -> "2")**
  
 **a match {**
  **case(12, x:String) => 12+x**
  
  **case _             => 34**
  **}**
    
    Options
    
    a)34
    
    b)12
    
    c)1234
    
    d)14
    
    e)122
    
    f)None


**4) output of this for comprehension**
    
   **for(i <- 1 to 3; j <- 1 to 3; if(i!=j)) println(5* i+j+"")**
   
   a) 7 8 11 13 16 17
   
   b) 8 12 13 16 17 18
   
   c)17 16 13 11 8 7
   
   d) Compilation Error


**5) What is the result type of a.flatten and a.flatmap**
      
**val a =List(List("A"),List("B"))**
      
**scala> a.flatten**
      
**scala> a.flatMap{x => x }**


**6)  What is the output of this operation List(1)::List(2,3)**

      a) List(1,2,3)
        
      b) List(2,3,1)
        
      c) List(List(1), 2, 3)                                                                                                                                                                                                                                                          
**7) What is value of x and y ?**

**scala> var x:Int =10**
      
**scala> var y:Int =20**
      
**scala> x=y=10**
  
  
          a) 10 and 20
          
          b) 20 and 10
          
          c) 10 and 10 
          
          d) compilation error
          
          e)none of the above 

**8) What is the output return type of this function**

**def fun(a: (Int => String =>Long => Int => Float)) = a(1)("hello")** 

**9) What is the output of this**

**for (i<-"scala";j <- 0 to 1)yield (i+j).toChar**
  
      a) stcdablmab
      
      b) vector(s,c,a,l,a,0,1)
      
      c)vector('s0','s1','c0','c1','a0','a1','l0','l1','a0','a1')
    
      d)s0s1c0c1a0a1l0l1a0a1
  
  
**10) what is the output**
    
  val a="Hello"
  
  val b= a:a.type
  
  println (b)
  
  options
  
  a) a
  
  b) Hello
  
  c) HelloString
  
  d) Error
  

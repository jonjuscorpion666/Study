Classes & Objects

->	In scala primitive data types are also considered as Objects.

->	Scala Int object is converted internally in java.int or Integer Objects.

->	Fuctions inside a class is know as methods and when it is inside object its know as functions.

-> methods without "=" will always return Unit.

-> Main function dont have "=" as its expected to return Unit and is called procedure

-> Methods that dont return a value is called procedure.

-> Shadowing is supported in scala . Ie local variable and external variables   can be used same name. And Inside method local variables with take preference

-> Singlton objects are same as static in java. Create only one instance. 

-> If object and class have same name it is called companion objects and can use members of method in companion object

-> objects are used in 2 types

	1) Companion object
	2) standalone object  

-> Any singleton object with a main method of the proper signature can be used as the entry point into an application.

->one way in which Scala is more object-oriented than Java is that classes in Scala cannot have static member.

->One difference between classes and singleton objects is that singleton ob- jects cannot take parameters, whereas classes can via primary and auxiliary constructors.

->You never have to instantiate a singleton object with the new keyword. Singleton objects are implemented as static values, so they have the same initialization semantics as Java statics. In particular, a singleton object is initialized the first time someone accesses it.
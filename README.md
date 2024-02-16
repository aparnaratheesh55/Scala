# Scala
* Scala is object oriented as well as functional and imperative programming.
* There is no primitive type in scala  so it is purely object oriented.
* Scala is immutable
* There is no need to specify the datatype in scala.
* Var is mutable, val is immutable.
* There are conditional expressions similar to java
* Scala pattern matching using  :- if _ is used it is considered to be as the default case
* Scala While,for loop
* Scala break statements
* Scala comments
# scala functions
```
object MainObject {  
   def main(args: Array[String]) {  
        functionExample()           // Calling function  
    }  
    def functionExample()  {        // Defining a function  
          println("This is a simple function")  
    }  
}
```
# mutable immutable and implicit variables in scala
* mutable variables is declared using var
* Immutable variables are declared using val
* implicit variables are declared
* Implicitely there is no declaration needed the type of variable will be understoode.
* Explicitely the variable can be declared by providing the data type explicitely.
# Type inference in any Any and AnyRef

* Any can be used if we dont know the type of data to be provided.
* AnyRef is used it excludes all primitive types .

# Arrays and collections 
* Array is mutable
* Collections can be both mutable and immutable-list,map,set,tuple,Seq
  * Scala support pure Functions -> which means the output only depends on input and not in any other without observable side effects.
* Scala is treated as object oriented as variables are also considered to be as objects so even primitive type is considered to be as object.

# Case class and Traits
* case class is created using case keyword.
* constructor paramter is automatically created.
* Traits are similar to multiple inheritance.

# Match clause
* It is used to provide pattern matching.
* Basically used as a case like structure
* In case the case with _ is treated as the default. 

# Scala Generics

* Scala generics provides a way to write reusable code and and help in abstracting over types.
# JSON parsing and JSON serialization

* JSON parsing means JSON scala objects
* JSON serialization encodes scala objects to JSON

# Protocols

Protocols remind me of extensions in the Java programming language. They can be thought of as a certificate. To define a protocol it is similar to how you would define a structure, class and enumeration. A protocol can be used to define certain methods, properties, or other requirement that suits a particular task or piece of functionality. 

## Defining a protocol:
-	protocol MyProtocol { // Define requirements }

## Adopting the protocol:
-	struct MyStruct: MyProtocol {		}
-	class MyClass: MyProtocol {		}


In the example below it has a superclass, and you must list the super class name before any protocols it adopts. 
-	class MyClass: Superclass, FirstProtocol, AnotherProtocol { // class definition goes here }

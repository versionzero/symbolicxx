SymbolicC++ uses C++ and object-oriented programming to develop a
computer algebra system. Object-oriented programming is an approach to
software design that is based on classes rather than procedures. This
approach maximizes modularity and information hiding. Object-oriented
design provides many advantages. For example, it combines both the
data and the functions that operate on that data into a single
unit. Such a unit (abstract data type) is called a class.

We use C++ as our object-oriented programming language for the
following reasons: C++ allows the introduction of abstract data
types. Thus we can introduce the data types used in the computer
algebra system as abstract data types. The language C++ supports the
central concepts of object-oriented programming: encapsulation,
inheritance, polymorphism (including dynamic binding) and operator
overloading. It has good support for dynamic memory management and
supports both, procedural and object-oriented programming. A less
abstract form of polymorphism is provided via template support. We
overload the operators

```
=, +,  -, *,  /
```
  
etc for our abstract data types, such as verylong integers, rational
numbers, complex numbers or symbolic data types. The vector and matrix
classes are implemented on a template basis so that they can be used
with the other abstract data types.

Another advantage of this approach is that, since the system of symbolic manipulations itself is written in C++, it is easy to enlarge it and to fit it to the special problem at hand. The classes (abstract data types) are included in a header file and can be provided in any C++ program by giving the command 

#include "ADT.h" 

at the beginning of the program.

For the realization of this concept we apply the following features of C++:

* The class concept
* overloading of operators
* overloading of functions
* inheritance of classes
* virtual functions
* function templates
* class templates
* Standard Template Library

The developed system SymbolicC++ includes the following abstract data types (classes):

* Verylong: handles very long integers
* Rational: template class that handles rational numbers
* Quaternion: template class that handles quaternions
* Derive: template class to handle exact differentiation
* Vector: template class that handles vectors
* Matrix: template class that handles matrices
* Array: template class that handles multi-dimensional arrays
* List: template class that handles linked lists
* Set: template class that handles finite sets
* Polynomial: template class that handles univariate polynomials
* Multinomial: template class that handles multivariate polynomials
* Symbolic: class that handles symbolic manipulations, such as rules, simplifications, differentiation, integration, commutativity and non-commutativity
* Equation: class that represents symbolic equations
* Type: handles the atom a LISP system
* Pair: handles the dotted pair for a LISP system, all the standard LISP functions are included
* Suitable type conversions between the abstract data types and between abstract data types and basic data types are also provided.

The advantages of SymbolicC++ are as follows:

* Object-oriented design and proper handling of basic and abstract data types.
* The system is operating system independent, i.e. for all operating systems powerful C++ compilers are available.
* The user is provided with the source code.
* New classes (abstract data types) can easily be added.
* The ANSI C++ standard is taken into account.
* The user only needs to learn C++ to apply the computer algebra system.
* Assembler code can easily be added to run on a specific CPU.
* Member functions and type conversion operators provide a symbolic-numeric interface
* The classes (abstract data types) are included in a header file and can be provided in any C++ program by giving the command #include "ADT.h" at the beginning of the program.
* The classes can be linked with Parallel Virtual Machine (PVM).
* Standard Template Library can be used with SymbolicC++.

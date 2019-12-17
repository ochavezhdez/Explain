Clean code
-  [ ] Pick one word per concept
-  [ ] Use solution/problem domain names
-  [ ] Do one thing
-  [ ] Don't repeat yourself
-  [ ] Explain yourself in code
-  [ ] Use Exceptions rather than Return codes
-  [ ] Don't return Null
-  [ ] Use Intention-revealing names
-  [ ] Classes should be small
-  [ ] Functions should be small
-  [ ] Make sure the code formatting is applied

General
-  [ ] Use checked exceptions for recoverable conditions and runtime exceptions for programming errors
-  [ ] Use of standard exceptions
-  [ ] Don't ignore exceptions
-  [ ] Check parameters for validity
-  [ ] Return empty arrays or collections, not nulls
-  [ ] In public classes, use accessor methods, not public fields
-  [ ] Minimize the scope of local variables
-  [ ] Refer to objects by their interfaces
-  [ ] Override hashCode when you override equals
-  [ ] Override toString
-  [ ] Avoid finalizers
-  [ ] Use enums instead of int constants
-  [ ] Synchronize access to shared mutable data
-  [ ] Prefer executors to tasks and threads

Security
-  [ ] Application to run with the least privilege mode required for functioning
-  [ ] Minimize the accessibility of classes and members
-  [ ] Document security related information
-  [ ] Input into a system should be checked for valid data size and range
-  [ ] Avoid excessive logs for unusual behavior
-  [ ] Release resources in all cases
-  [ ] Purge sensitive information from exceptions
-  [ ] Do not log highly sensitive information
-  [ ] Avoid dynamic SQL, use prepared statement
-  [ ] Limit the accessibility of packages, classes, interfaces, methods, and fields
-  [ ] Limit the extensibility of classes and methods
-  [ ] Validate inputs
-  [ ] Validate output from untrusted objects as input
-  [ ] Define wrappers around native methods
-  [ ] Make public static fields final
-  [ ] Avoid exposing constructors of sensitive classes
-  [ ] Avoid serialization for security-sensitive classes
-  [ ] Guard sensitive data during serialization
-  [ ] Be careful caching results of potentially privileged operations
  
Performance
-  [ ] Avoid excessive synchronization
-  [ ] Keep Synchronized Sections Small
-  [ ] Beware the performance of string concatenation
-  [ ] Avoid creating unnecessary objects
-  [ ] Select correct cursor
-  [ ] Select correct fetch size
-  [ ] Do not use “select * from table”
-  [ ] Always check driver features implementation
-  [ ] Always close Statement and ResultSet objects as soon as possible
-  [ ] Use the type-correct get() method, rather than getObject()
-  [ ] Extract data from ResultSet using index instead columns names
-  [ ] Use primitives where possible
-  [ ] Use StringBuilder to Concatenate Strings Programmatically
-  [ ] Always use Interface when implement a collection

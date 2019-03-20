# INFOTC2040-CsharpQuestions1
## John Williams III
----------------------------------------
### Q: What is a namespace?
- A namespace provides a way to keep one set of names separate from another. It is defined by the keyword namespace.

### Q: What are value types?
- There are two types of value types in C#. Structs and Enumerations. A struct type is a value type that is typically used to encapsulate small groups of related variables. Enumerations have a distinct type with a set name of constants called an enumerator list. When you assign a new value to a variable of a value type, that value is copied. Value types directly contain their data. 

### Q: What are reference types?
- With reference types, two variables can reference the same object; therefore, operations on one variable can affect the object referenced by the other variable. Reference types include class, interface, delegate, dynamic, object, and string.

### Q: What is an automatic property and how is it useful?
- auto-implemented properties make property-declaration more concise when no additional logic is required in the property accessors. They also enable client code to create objects.

### Q: What is the purpose of using statement?
- The using statement obtains one or more resources, executes a statement, and then disposes of the resource.

### Q: What are dynamic type variables?
- A dynamic type is a static type. At compile time, an element that is typed as dynamic is assumed to support any operation.

### Q: What is the purpose of the is operator?
- The is operator checks for type compatibility. It returns true if the operand can be cast to the type specified.

### Q: What are generics and how is using them useful?
- Generics are used to maximize code reuse, type safety, and performance. 

### Q: What is the scope of a public member of a class?
- Public, private, protected, internal, and protected internal.

### Q: Can you create a function that can accept a varying number of arguments?
- Yes, an example of how to accomplish this would be using params object[] args.

### Q: How do you sort an array?
- Use Array.Sort().

### Q: What is a nullable type and what purpose does it serve?
- You use a nullable type when you need to represent the undefined value of an underlying type.

### Q: What is an enumeration?
- Enumerations are value data type. Enumerations contain thier own values and cannot inherit or cannot pass inheritance.

### Q: What is inheritance?
- Inheritance allows you to define a child class that reuses (inherits), extends, or modifies the behavior of a parent class. The class whose members are inherited is called the base class. The class that inherits the members of the base class is called the derived class.

### Q: Is multiple inheritance supported?
- No, C# and .NET only support single inheritance. 

### Q: What is the purpose of as operator?
- You can use the as operator to perform certain types of conversions between compatible reference types or nullable types. 

### Q: What is an object?
- An object is an instance of a class that is created dynamically.

### Q: What is the difference between a struct and a class?
- Classes are reference types, structs are value types. 

### Q: What is the difference between continue and break statements?
- Using break statement,you can 'jump out of a loop' whereas by using continue statement, you can 'jump over one iteration' and then resume your loop execution.

### Q: What is this and how is it used?
- The this keyword refers to the current instance of the class and is also used as a modifier of the first parameter of an extension method.

### Q: What is try and catch and when are they used?
-The try-catch statement consists of a try block followed by one or more catch clauses, which specify handlers for different exceptions.

### Q: How is exception handling done?
- The catch portion of a try, catch, finally, throw catches an exception with an exception handler and the throw portion throws an exception when it shows up. 

### Q: What is finally and what is its purpose? 
-The finally block is used to execute a given set of statements, whether an exception is thrown or not thrown.

### Q: List the differences between Array and ArrayList.
- The differences between an Array and an ArrayList in C# are that Arrays all must have the same data types and have a fixed length that cannot be changed during runtime. ArrayLists on the other hand can store the values of different data types or the same data type. ArrayLists also allow the size of an array to increase or decrease dynamically. Arrays cannot accept null values while ArrayLists can accept null values. 

### Q: What is an object? 
- An object is an instance of a class that is created dynamically.

### Q: Define constructor. 
- Constructors have the same name as the class or struct, and they usually initialize the data members of the new object

### Q: When can var be used to declare a variable and how is the type for the variable determined?
- Var can only be used when a local variable is declared and initialized in the same statement; the variable cannot be initialized to null, or to a method group or an anonymous function. var cannot be used on fields at class scope. Variables declared by using var cannot be used in the initialization expression.

### Q: What is an abstract class?
- An abstract class cannot be instantiated. The purpose of an abstract class is to provide a common definition of a base class that multiple derived classes can share.

### Q: What is an interface?
- An interface contains definitions for a group of related functionalities that a class or a struct can implement.

### Q: What is a method?
- A method is a code block that contains a series of statements. A program causes the statements to be executed by calling the method and specifying any required method arguments. In C#, every executed instruction is performed in the context of a method.

### Q: What is a property?
- A property is a member that provides a flexible mechanism to read, write, or compute the value of a private field. Properties can be used as if they are public data members, but they are actually special methods called accessors. 

### Q: What is an access specifier?
- All types and type members have an accessibility level, an access specifier controls whether they can be used from other code in your assembly or other assemblies.

### Q: What access specifiers are supported and what do they mean?
- public: The type or member can be accessed by any other code in the same assembly or another assembly that references it.
- private: The type or member can be accessed only by code in the same class or struct.
- protected: The type or member can be accessed only by code in the same class, or in a class that is derived from that class.
- internal: The type or member can be accessed by any code in the same assembly, but not from another assembly.
- protected internal: The type or member can be accessed by any code in the assembly in which it is declared, or from within a derived class in another assembly.
- private protected: The type or member can be accessed only within its declaring assembly, by code in the same class or in a type that is derived from that class.

### Q: What is a collection?
- Collection classes are specialized classes for data storage and retrieval. These classes provide support for stacks, queues, lists, and hash tables. 

### Q: What is a Hash Table?
- A hash table is used when you need to access elements by using key, and you can identify a useful key value. Each item in the hash table has a key/value pair. The key is used to access the items in the collection.

### SOURCES
- https://www.tutorialspoint.com/csharp/index.htm
- https://docs.microsoft.com/en-us/dotnet/csharp/index

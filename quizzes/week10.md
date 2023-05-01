# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace is used to declare a scope and create a reference value that allows a user to call upon the scoped content in other parts of the application.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structures are value types and classes are reference types. The structure references the direct value of a part of the code. A class is the name that is designated to direct you to the value elsewhere in the code.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void is used when there is no return type
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public makes this function available to anyone in the application.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is the type of data that is being used.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract is preventing the user from seeing the class Car so they do not have access to change it.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A virtual makes it so a value can be overridden or changed later in the function.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Private, Public, Internal, Protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The type or member can be accessed only by code in the same struct.
```
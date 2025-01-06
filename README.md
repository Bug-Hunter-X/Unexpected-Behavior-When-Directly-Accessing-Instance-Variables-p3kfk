# Unexpected Behavior When Directly Accessing Instance Variables in Ruby
This example demonstrates a potential issue when directly manipulating instance variables using `instance_variable_set` in Ruby.  While sometimes useful for metaprogramming, it can lead to reduced code clarity and maintainability, and can easily introduce subtle bugs.
The example shows how modifying an instance variable directly through `instance_variable_set` can change the object's state unexpectedly if not handled carefully.  A preferred approach is to use accessor methods to maintain encapsulation and control.
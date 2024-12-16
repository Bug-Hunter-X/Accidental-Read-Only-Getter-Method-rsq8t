# Accidental Read-Only Getter Method in Ruby

This example showcases a common error in Ruby where a method intended to be a setter accidentally behaves like a read-only getter due to a missing setter method.  In the `MyClass` example, the `value` method only returns the internal `@value` instance variable, rather than setting it.  This can lead to unexpected behavior and bugs in your application.

The `bug.rb` file contains code demonstrating this issue.  The `bugSolution.rb` file shows how to correctly implement a setter method.
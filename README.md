# Ruby Immutability Bug

This repository demonstrates a subtle bug in Ruby related to the misconception of modifying instance variables through getter methods.  The provided code shows how assigning a value through a getter method doesn't actually modify the object's internal state.

The `bug.rb` file contains the buggy code, and `bugSolution.rb` provides the correct way to modify the instance variable.

This example highlights the importance of understanding Ruby's object model and how to correctly modify instance variables.
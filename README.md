# Ruby Bug: Unexpected Instance Variable Modification

This repository demonstrates a common, yet subtle, bug in Ruby related to directly modifying instance variables using `instance_variable_set`.  While functional, this practice undermines encapsulation and can lead to unexpected issues in larger applications.

The `bug.rb` file shows how modifying an instance variable directly using `instance_variable_set` bypasses method logic and can easily introduce hard-to-debug errors.  The `bugSolution.rb` file demonstrates a more robust approach using accessors.

## How to Reproduce

1. Clone the repository.
2. Run `ruby bug.rb`
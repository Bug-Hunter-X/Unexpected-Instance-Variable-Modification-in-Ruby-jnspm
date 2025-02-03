# Unexpected Instance Variable Modification in Ruby

This example demonstrates a subtle issue in Ruby related to modifying instance variables directly using `instance_variable_set`.  While using a symbol is the standard and recommended approach, using a string can lead to unexpected results.

The `bug.rb` file contains code that showcases this behavior. The solution, presented in `bugSolution.rb`, highlights the correct way to handle instance variable modification.

## How to reproduce

1.  Clone this repository.
2.  Run `ruby bug.rb`.
3.  Observe the unexpected output.
4.  Compare it with the corrected version in `bugSolution.rb`.

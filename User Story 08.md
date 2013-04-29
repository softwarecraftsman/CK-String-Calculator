# Summary
As an end-user, I want to be able to define multiple delimiters, so that I may sepcify more than one delimiter for my string.

# Acceptance Criteria
- User can define multiple delimiters
- Multiple delimiters are comma separated on the first line

# Example Inputs and Outputs
- `"//[***],[$]\n1$2***3"`	=>	6

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
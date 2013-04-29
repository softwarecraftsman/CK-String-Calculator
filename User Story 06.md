# Summary
As an end-user, I want the calculator to ignore numbers larger than 1000 when calculating the sum, so I may calculate numbers smaller than 1000 without fear of it including larger numbers.

# Acceptance Criteria
- Calculator ignores numbers greater than 1000 in summation

# Example Inputs and Outputs
- `"1\n2,3"`		=>	6
- `"1,2,10001"`	=>	3

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
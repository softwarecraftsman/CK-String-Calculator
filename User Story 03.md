# Summary
As an end-user, I want the calculator to accept a new line character as the delimiter in addition to a comma, so that I may pass a list of numbers delimited by new lines and calculate their sum.

# Acceptance Criteria
- Calculator accepts numbers separated by a comma
- Calculator accepts numbers separated by a new line character
- Calculator accepts numbers separated by any combination of a comma or a new line character

# Example Inputs and Outputs
- `"1\n2,3"`	=>	6
- `"1,\n2"`	=>	input is invalid; but do not need to verify

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
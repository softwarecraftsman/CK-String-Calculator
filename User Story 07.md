# Summary
As an end-user, I want to be able to define a delimiter of variable length, so that I may better control what delimiters I use to calculate a sum.

# Acceptance Criteria
- Defined delimiter can be of n length
- Delimiter value is wrapped by `[` and `]`

# Example Inputs and Outputs
- `"//[***]\n1***2***3"`	=>	6
- `"[[]]\n1[]2[]3[]"`		=>	6

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
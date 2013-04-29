# Summary
As an end-user, I want the calculator allow me to define my own, single delimiter, so that I may customize what delimiter my string of numbers will utilize.

# Acceptance Criteria
- Calculator supports multiple delimiters
- If a custom delimiter is used, the first line will be used to define the delimiter in the following format:
	- `"//[delimiter]\n[numbers...]"`
- First line is optional
- All previously defined delimiters still work and do not need to be defined

# Example Inputs and Outputs
- `"2,3"` =>	5
- `"5"`	=>	5
- `""`	=>	0

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
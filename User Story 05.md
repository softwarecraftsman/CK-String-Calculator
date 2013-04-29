# Summary
As an end-user, I want the calculator to throw an exception for a negative number and show all negative numbers in the list upon throwing the exception, so that I may quickly identifiy the negative numbers to be removed from my string.

# Acceptance Criteria
- Calculator throws exception if a negative number is present
- Exception contains all negative numbers in the string to be delivered to the end-user
- If a custom delimiter is used, the first line will be used to define the delimiter in
- Exception message should read as follows: "Negative numbers are not allowed; please correct these numbers: [numbers,]" where [numbers,] is a comma delimited list of all negative numbers in the original string 

# Example Inputs and Outputs
- `"2,3"`				=>	5
- `"-1"`				=>	throws exception
- `"1,5,-5,5,-10"`	=>	throws exception with list of numbers: `"-5,-10"`

# Remember
- Start with the simplest test case of an empty string and move to 1 and 2 numbers
- Solve things as simply as possible so that you force yourself to write tests you did not think about
- Refactor after each passing test
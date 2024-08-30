# Printing ASCII art using define and raw strings
Function Definitions:
print_ryan():
print_joseph():
  Defines two variables: blue and reset, which contain ANSI escape codes for text color formatting.

Escape Sequences: The \033[34m sequence sets the text color to blue, while \033[0m resets the color.
 blue = '\033[34m' sets the text color to blue.
 reset = '\033[0m' resets the text formatting to default.

Raw Strings: Utilizes raw string formatting (rf"") to handle special characters and escape sequences seamlessly.
 The rf"" syntax allows for raw string formatting. Raw strings treat backslashes (\) as literal characters, and the f allows for variable interpolation.

### Explanation:

- **Header**: Provides a brief title and description of what the project does.
- **Function Definitions**: Briefly explains the purpose of each function.
- **Code Overview**: Shows the code used in the project.
- **Escape Sequences**: Details the ANSI escape codes used for color formatting.
- **Raw Strings**: Explains the usage of raw formatted strings in Python.
- **How It Works**: Summarizes the functionality of the code.
- **Usage**: Instructions for running the script and viewing the output.

Feel free to copy and use this `README.md` file in your GitHub repository!


# Printing ASCII Art Using Functions and Raw Strings

This project demonstrates how to create and print ASCII art with colored text using Python. The ASCII art is styled using ANSI escape codes and raw string formatting.

## Function Definitions

### `print_ryan()`

This function prints an ASCII art representation of "Ryan" in blue. It uses ANSI escape codes to set the color and reset it after printing.

### `print_joseph()`

This function prints an ASCII art representation of "Joseph" in blue, similarly using ANSI escape codes for coloring and resetting.

## Code Overview

The script defines two functions that utilize ANSI escape codes and raw strings:

```python
def print_ryan():
    blue = '\033[34m'
    reset = '\033[0m'
    print(rf"""{blue}

  _ \ \ \  /  \     \ | 
    /  \  /  _ \   .  | 
 _|_\   _| _/  _\ _|\_| 
                        
{reset}""")

def print_joseph():
    blue = '\033[34m'
    reset = '\033[0m'
    print(rf"""{blue} 

     |  _ \    __|  __|  _ \ |  | 
  \  | (   | \__ \  _|   __/ __ | 
 \__/ \___/  ____/ ___| _|  _| _| 
                                  
{reset}""")

print_ryan()
print_joseph()

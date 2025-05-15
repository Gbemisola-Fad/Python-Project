# Caesar-Cipher

###### Using Functions to Implement a Caesar Cipher
##### I wrote a program that implements a Caesar cipher, which is a simple method of encryption.
##### A Caesar cipher takes the letters of a message and shifts each letter along the alphabet by a certain number of places.
##### In this lab, We created user-defined functions Use several functions to implement a Caesar cipher encryption program

## Description
##### This project implements a Caesar cipher, a basic encryption technique that shifts letters in a message by a specified number of positions in the alphabet. The program allows users to encrypt and decrypt messages using this simple yet effective method of encryption.

## Technologies Used
##### Python - The programming language used to implement the Caesar cipher. User defined Functions - The program is structured using multiple functions to enhance modularity and readability

## Implementation Details
##### Functions - The program is organized into several user-defined functions, each responsible for a specific task
##### encrypt(message, shift) - Takes a plaintext message and a shift value, returning the encrypted message.
##### decrypt(ciphertext, shift) - Takes an encrypted message and a shift value, returning the original plaintext message.
##### shift_character(char, shift) - A helper function that shifts a single character by the specified amount, handling both uppercase and lowercase letters while preserving non-alphabetic characters.
##### main() - The main function that drives the program, handling user input and displaying results.

## Design Considerations
##### Modularity - The use of functions promotes code reusability and makes the program easier to maintain and extend
##### Input Validation - The program includes basic input validation to ensure that the shift value is within a valid range and that the input message is properly formatted
##### Character Handling - The implementation ensures that non-alphabetic characters remain unchanged during encryption and decryption, preserving the integrity of the original message.


## 2. Calculating-the-Net-Charge
##### Calculating the Net Charge of Insulin by Using Python Lists and Loops

## Discription
##### Created a dictionary of pKa values (which indicate the strength of an acid) that will be used in the net charge calculations
##### Used the count() method to get a count of amino acids
##### Used a while loop to calculate the net charge of insulin from pH 0 to pH 14
##### The dictionary pKa_values contains the pKa values for the amino acids that can contribute to the charge of insulin.
##### The insulin_sequence is a string representing the sequence of insulin
##### The dictionary comprehension counts the occurrences of each amino acid
##### The while loop iterates through pH values from 0 to 14. For each pH, it calculates the net charge based on the pKa values and the counts of each amino acid
##### If the pH is below the pKa, the amino acid is positively charged; if above, it is negatively charged

## Design Considerations
##### the results are printed, showing the pH and the corresponding net charge
##### You can modify the insulin_sequence and the pKa_values as needed to fit your specific requirements
##### This project calculates the net charge of the insulin protein at varying pH levels, ranging from 0 to 14, by analyzing the contributions of specific amino acids based on their pKa values.
##### The project utilizes Python, leveraging dictionaries to store pKa values and lists to represent the insulin sequence
##### It employs a while loop to iterate through pH values, calculating the net charge by counting the occurrences of relevant amino acids and determining their charge state based on the relationship between pH and pKa
##### The results are then printed in a clear format, showing the net charge at each pH level

## 3. Caesar-Cipher-Program
#### Debugging the Caesar Cipher Program

## Description
##### This project focuses on debugging various versions of a Caesar cipher program using the Python Debugger (pdb) The goal is to identify and fix bugs in the implementation of the Caesar cipher, ensuring that the encryption and decryption processes work correctly

## Technologies Used
##### Python: The programming language used for implementing the Caesar cipher and debugging
##### Python Debugger (pdb): A built-in module that provides an interactive debugging environment for Python programs

## Implementation Details
##### Debugging Processn - The project involves using pdb to step through the code, inspect variables, and evaluate expressions to identify logical errors and bugs in the Caesar cipher implementation
##### Setting Breakpoints - Breakpoints are set at critical points in the code to pause execution and examine the program's state
##### Stepping Through Code - The debugger allows for stepping through the code line by line to observe the flow of execution and identify where the logic may be failing
##### Inspecting Variables - The ability to inspect variable values at different stages of execution helps in understanding how data is being manipulated and where errors may arise

## Design Considerations
##### Error Identification - The debugging process focuses on identifying common issues such as incorrect character shifting, handling of edge cases, and ensuring that the program correctly preserves non-alphabetic characters
##### Documentation of Bugs - Each bug identified during the debugging process is documented, along with the steps taken to resolve it, providing a clear record of the debugging journey
##### Testing - After fixing bugs, the program is tested with various inputs to ensure that the encryption and decryption functions work as intended

# 4. Creating-File-Handlers-&-Modules
##### Creating File Handlers and Modules for Retrieving Information about Insulin

## Description 
##### This project involves creating a Python module to retrieve and analyze information about human insulin from a JSON file.
##### The module loads the data, parses the JSON structure, and calculates the rough molecular weight of human insulin based on the provided sequence.

## Technologies Used Python 
##### The primary programming language used for developing the module and handling data
##### JSON Module - A built-in Python module used to parse JSON data from files
##### File Handling - Techniques for opening, reading, and processing files in Python

## Implementation Details 
##### A custom Python module is created to encapsulate the functionality for loading and processing insulin data
##### File Handling - The module includes functions to open a JSON file, read its contents, and load the data into a Python dictionary using the json.load() method
##### Data Parsing - The JSON structure is parsed to extract relevant information about insulin, such as its amino acid sequence and other properties
##### Molecular Weight Calculation - A function is implemented to calculate the rough molecular weight of human insulin based on its amino acid sequence
##### This involves summing the weights of individual amino acids as defined in the project

## Design Considerations
##### The module includes error handling to manage potential issues such as file not found errors and JSON parsing errors
##### Modularity - The code is organized into functions to promote reusability and clarity, making it easier to maintain and extend in the future
##### Data Validation - Basic validation checks are implemented to ensure that the amino acid sequence is valid before calculating the molecular weight

# 5. System Adminstration
##### Introducing System Administration with Python
##### Using Linux to do many administrative tasks from the terminal, or the Bash command line. 
##### Python provides several modules that you can also use to run commands on the command line. In this lab, you will use os.system() and subprocess.run() to run Bash commands from Python.

## Descrription
##### Use os.system() to run a Bash command Use subprocess.run() to run Bash commands
##### This project demonstrates how to leverage Python for system administration tasks by executing Bash commands directly from Python scripts.
##### It provides a practical introduction to using the os and subprocess modules for running shell commands, making it easier to automate and manage system operations.

## Technologies Used
##### Python - The primary programming language used for scripting
##### Linux - The operating system environment where the Bash commands are executed
##### os module - A built-in Python module used to interact with the operating system, allowing for command execution
##### subprocess module - A more powerful module than os for spawning new processes, connecting to their input/output/error pipes, and obtaining their return codes

## Implementation Details
##### os.system() - This function is used to run simple Bash commands. It executes the command in a subshell and returns the exit status of the command
##### subprocess.run() - This function provides more control over command execution, allowing for better error handling and output management
##### It can capture standard output and error, making it suitable for more complex command executions

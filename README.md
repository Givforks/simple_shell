C - Simple_Shell.

A project by Givens and Gabriel.

0x16. C - Simple Shell                                                     
This project aim at nurturing our poisitive mindset to meet the ALX standard of learning and to prepare us for advance project task. Also the shell program include system call, process, bit manipulation, file managment, error handling and the task itself.

This program was written entirely in original C, so Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh).

/**** Feature  ****/
Display a prompt and wait for the user to type a command.
- A command line always ends with a new line.
- Handle the Ctrl-C to not terminate the shell.
- Handling the command seperator `;`.
- Handling `&&` and `||` logical operators.
- Handle variable replacements `$?` and `$$`.
- Handle the comments `#`.
- Support the history feature.
- Support the file input.
- Handle errors.
- Hndling the “end of file” condition (Ctrl+D).
- Hanling the command line with arguments.
- Handle the PATH.
- Support the exit features and the exit status.

/** Builtins **/
The shell support for the following built-in commands
- Command             - Definition                                                                                
- ******************* - ***************************************************************************************** 
- exit [n]            - Exit the shell, with an optional exit status, n.                                          
- env                 - Print the environment.                                                                    
- setenv [var][value] - Set an environment variable and value.If the variable exists, the value will be updated. 
- alias[name[='value]]- Reads aliases name                                                                        
- unsetenv [var]      - Remove an environment variable.                                                           
- cd [dir]            - Change the directory.                                                                     
- help [built-in]     - Read documentation for a built-in.   

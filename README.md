# C++ Input/Output

## C++ Input Output in command line form.

# Here is the code of the .cpp file or code of C++ file.

include <iostream>
    
include <string>
    
include "InputOutput.h"
    

int main()
    
    
{
    
    std::string nameofuser;
    
    std:int16_t firstnum;
    
    std:int16_t secondnum;
    
    std::cout << "Hello World! Your name is: ";
    
    std::cin >> nameofuser;
    
    std::cout << "Your name is "+nameofuser+"\n\t";
    
    std::cout << "Enter a number, this is a sum\n\t";
    
    std::cin >> firstnum;
    
    std::cout << "Enter next number.\n\t";
    
    std::cin >> secondnum;
    
    std::cout << "\n\t The result is \n";
    
    std::cout << firstnum+secondnum;
    
}
    
  
# Here is the code of the .h file or header file.
  
###### #pragma once

int main();

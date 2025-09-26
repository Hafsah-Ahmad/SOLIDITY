                                      SOLIDITY
            Object-oriented, high level programming language for implementing smart contracts.
            -It is a curly brace programming language.
            -Influenced by c++, python and javascript.
            -Supports complex user defined programming, libraries and inheritance.

                                     SOLIDITY VARIABLES
            used to store and manage data within smart contracts.
            - they are fundamental components of any programming language.
            -allows user to change and retrieve the stored information.
            - three different type of variables.
                        ~STATE=(declared inside the functons,only accessible within the scope of function, used for temporary storage)

                        ~LOCAL= (used to store information on the ethereum blockchain, represent long term state of contract, used to store important data)

                        ~GLOBAL= (special variables that are accessible from any contract or function in your solidity smart contract, like msg.sender, Tx.Origin etc)
            
                                 STANDARDS FOR DECLARING VARIABLES
                         
            -Never use reserve keywords as variables like bool, int etc.
            -Shouldn't start with a number.
            -Solidity is case sensitive.
            -use camel casing.
             
                                  SOLIDITY OPERATORS
            symbols or keywords that represent various operations.
            it supports wide range of operators.
            some common tyoes are;
                            -Arithmatic operators
                            -Comparison operators
                            -Logical operators
                            -Bitwise operators
                            -Assignment operators
                            -Conditional operators
                            -Type conversion operators

                                 FUNCTIONS
               
          -executable units of code
          -usually defined inside a contract but can be also defined outside the contract
          -reuseable codes, saving memory.
                               
                               DECLARATION
               -keyword "function"
               -unique name
               -data type and variable name
               -return statement
               -visibility

                               STATE MUTABILITY
               
               desribes whether the function reads, modifies or doesn't affect the contract's state.

                              TYPES OF FUNCTIONS

                    -view function
                    -pure functions
                    -pullback functions

                             STORAGE AND MEMORY
           Storage=
                  -Permanent data stored on the blockchain.
                  -Used for state variables.
                  -Expensive (gas-wise).
                   Example: uint public x;

          Memory=
                 -Temporary data used during function execution.
                 -Cleared after the function ends.
                 -Cheaper than storage.
                 -Used in function parameters or local variables.
                 Example: function show(uint[] memory arr) public view { }
            

            I WILL UPDATE TOMORROW.
            I WILL UPDATE TOMORROW.
            
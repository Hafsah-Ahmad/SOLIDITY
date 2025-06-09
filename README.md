                                                                 Solidity Quick Notes
                                                                 
Solidity is an object-oriented, high-level programming language used to implement smart contracts on Ethereum and similar blockchain platforms.

 Key Features=
-Curly-brace syntax (inspired by C++, Python, JavaScript)
-Supports complex user-defined types, libraries, and inheritance

 Solidity Variables=
Variables are essential for storing and managing data within smart contracts. Solidity provides three types of variables:

Local Variables=
Declared inside functions
Temporary storage, accessible only within function scope

State Variables=
Stored permanently on the blockchain
Represent the long-term state of a contract

Global Variables=
Special variables available throughout the contract
Examples: msg.sender, tx.origin, block.timestamp, etc.

Variable Declaration Rules=
-Avoid using reserved keywords (e.g., bool, int) as names
-Do not start variable names with numbers
-Solidity is case-sensitive
-Use camelCase for naming conventions

SOLIDITY OPERATORS=
Solidity supports a wide range of operators to perform various operations:
-Arithmetic Operators (+, -, *, /, %)
-Comparison Operators (==, !=, <, >, <=, >=)
-Logical Operators (&&, ||, !)
-Bitwise Operators (&, |, ^, ~, <<, >>)
-Assignment Operators (=, +=, -=, etc.)
-Conditional (Ternary) Operator (condition ? trueExpr : falseExpr)
-Type Conversion Operators (uint(x), address(x))

FUNCTIONS IN SOLIDITY=
-Executable units of code
-Usually defined inside a contract but can also be defined outside
-Reusable code, saving memory and gas

DECLARATION OF FUNCTION=
-Keyword: function
-Unique function name
-Data type and variable name as parameters
-Return statement (if any)
-Visibility specifier (public, private, etc.)

STATE MUTABILITY= 
-Describes whether the function reads, modifies, or doesn’t affect the contract’s state.
-view – reads state
-pure – neither reads nor modifies
-payable – can receive Ether

TYPES OF FUNCTION=
-View Functions – read state variables, no changes
-Pure Functions – do not read or write any state
-Fallback Functions – handle unknown function calls or direct Ether transfers

STORAGE VS MEMORY=
Storage=
-Permanent data stored on the blockchain
-Used for state variables
-Expensive in gas
-Example: uint public x;

Memory=
-Temporary data used during function execution
-Cleared after the function ends
-Cheaper than storage
-Used for function inputs or temporary variables
-Example:
function show(uint[] memory arr) public view { }

I WILL UPDATE TOMORROW.
I WILL UPDATE TOMORROW.
i will get back here soon.
charger ly gai meraaaaa.



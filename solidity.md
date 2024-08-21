# ide : remix
- first we declere licence number
- version of solidity version
- this remix support solidity and vyper language

# Solidity compilation process
- .sol/solidity compiler/ABI(abstract binary interface)/byte code/ethereum blockchain
- when we compile smart contract so this will generate ABI and byte code.

# Rickybe faucet
- this will generate fake ether

# contract deployment
- two vm javascript and remix but both are same

# DAO attack in solidity
- function which do ether widraw and this function call recurseivlly so this cause empty wallate

# state variable in solidity
- this will declare at top of the contract 
- we will asign value at declaration time or using constuctor

# local variable in solidity
- this variable is store in stack not in blockchain
- we use "pure" function which indicate that this function will not change anything in state variable
- at local area when we need to use string so we need to use memory keywork for declare string and also note that at state level we don't use memory keyword

# funciton in solidity
- when we declare state variable with public so we don't need to create getter fuction 

# view vs pure
- using pure we cant read or write state variable and using view use get as well as set value of state variable

# constructor
- this funciton call auto when contract call

# integers
- int8 to int256
- also uint8 to uint256
- and also uint8 and int8 also called int alias

# overflow and underflow
- batchoverflow and interger overflow in ERC20 token 
- this problem is solved in 0.8.0 but this problem is in 0.5.0

# Arrary
- fix and dynemic size array two type.
- arr.lenght this is function which return length of array
- dynemix size array : 

# bytes array in fixed array
- this is fixed size array 
- also this is immutable

# bytes array in dynamic array
- when we write only bytes so this is dynamic size array

# loops
- we need to wrap up in fuction otherwise this will give error 

# ifelse and boolen
- if else is same as other language
- boolean : bydefault value is false

# structure
- using this we will create our own datatype
- using constructor and function both are in remix ide you can check

# Enum
- use of this is incrase readability of code and give user best experiance

# mapping
- concept of key and value
- this is succesor of array because when we need to create 0, 5, 100 index array so we need to use mapping
- also we map structure like this way and attach at key with many value
- key cannot be type of mapping, struct, enum, array

# storage vs memory
- storage is blockchain memory like this will store state variable
- memory is store local variable
- storage need gas fee
- memory no gas fee
  
# global variable
- 
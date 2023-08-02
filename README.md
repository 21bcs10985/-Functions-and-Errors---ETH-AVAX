# ETH + AVAX PROOF: Intermediate EVM Course-

## Functions-and-Errors---ETH-AVAX
The project that Metacrafters have assigned in the Blockchain course.
## Description

This repository contains the assignment that is made during the learning process of blockchain. In this assignment, I have been given a task to write a smart contract that has the implementation of all three Error management statements Require(), Revert(), and Assert(). To meet all the requirements I have created a smart contract  FunctionAndError, Inside that i have created a function SetValue which takes the input from the user and then stores it as the owner and its initial value. After the value has been assigned to the variable next i have created another function Withdrew which has Require() statement whose task is to check the user who is trying to access the account is the owner or not if yes then proceed otherwise reverse the transaction and then i have written an if-else statement which is checks for funds available or not if funds are not available then the transaction is reverted.
At the end  i have created a function Assert whose task is to verify is the transaction is reverted due to insufficient funds is true or not.

Statement: 
1.   _require()
   
         require(msg.sender == Address, "Only the owner can withdraw");

2.   revert()
   
         if (AvailableBalance < Amount) {
            revert("No funds available to withdraw");
          }

  3.    assert()
  
          assert(AvailableBalance < Amount);_


### Link of Assignment  
* [Functions and Errors (Module_1.sol)](https://github.com/21bcs10985/-Functions-and-Errors---ETH-AVAX/blob/main/FunctionAndError.sol)


## Getting Started
### Installing
There is no need to install any software, you can compile and run the code by visiting the given websites form your browser only.
* [Click here to run .js file](https://gitpod.io/workspaces/)
* [Click here to run .sol file](https://remix.ethereum.org/)

### Executing program
To execute the code you can simply copy the code form the repository and then paste it too the compiler and then click on compile or run code.

I have also provided my Loom video so that you can take the reference:


### Loom Links
* [Functions and Errors (Module_1.sol)](https://www.loom.com/share/5b3024db5e0b4ac2bf1821ab5d678be6) 

## Author
This repository is under Harsh Deo Ravi.

Contact info:

Email: harshdeoravi@gmail.com

This is a Solidity program for error handling.

Three methods are used for error handling:
1. require() - it validates the condition given. If condition is true then function is executed otherwise it passes the message back to caller.
2. revert() - if there is error it reverts the current call and returns to initial state. Remaining gas is returned to user.
3. assert() - it only validates the condition. If condition fails execution is terminated.


   This project is licensed under the MIT License

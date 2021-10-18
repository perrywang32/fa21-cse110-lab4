Questions and Answers for part 1
1) Line 9 prints: "values added: 20"
2) Line 13 prints: "final result: 20"
3) Line 9 prints: "values added: 20"
4) Line 13 prints: "Process exited with code 1... Uncaught ReferenceError: result is not defined". The error occurs because result variable is only accessible within the block that result variable is declared in as a let type.
5) Line 9 returns a Process exited with code 1... Uncaught TypeError: Assignment to constant variable. The error occurred because we tried to reassign values to a const variable, which is never quite allowed.
6) Line 13 is never accessed because the program stops at the error at line 9, which is an aforementioned type assignment error.

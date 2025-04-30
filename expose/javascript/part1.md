1. Line 9 will output 'values added: 20' into the console.
2. Line 13 will output 'final result: 20' into the console
3. You shouldn't use var because it's scope is function wide, which can lead to possible conflicts or unexpected behavior (name conflicts, scoping issues, etc...)
4. Line 9 will output 'values added: 20' into the console.
5. The code returns an error because the scope of 'result' is not function wide, and is only accessable within the if statement.
6. The code returns an error because the const 'result' is reassigned after declaring it a constant and assigning a value.
7. The code returns an error because the const 'result' is not defined outside of the if statement.
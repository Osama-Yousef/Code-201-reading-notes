# Read:10 Summary
## From the Duckett JS book:
***JavaScript book, Ch. 10, “Error Handling & Debugging”***


> If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 
Debugging 

> Debugging is the process of finding errors. It involves a process of deduction. 

* The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 
* If you know that you may get an error, you can handle it gracefully using the `try, catch, finally` statements. Use them to give your users helpful feedback. 
* In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object. 
* Error objects can help you find where your mistakes are and browsers have tools to help you read them. 


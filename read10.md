#  Error Handling & Debugging

when writing a long script no body gets everything right in the first attempt thats why you need to creat the instructions that allow the computer to solve it . 
 
their are three ways to determain what went wrong with your code:
* the console and dev tools : tools build into the browser that help you hunt for errors. 
* common problems : common sources of errors and how to solve them. 
* handling errors : how code can deal with potential errors gracefully. 
#### order of execution 

it's important to understand how codes are executed in order to know what mistakes you made. 

#### execution contexts 

there is one global execution context and each function creats a new execution context and they correspond to variable scope. 

###### execution context: 
* global context.
* function context. 
* eval context (not shown). 
###### variable scope: 
* glopal scope. 
* function-level scope. 


#### The Stack 

when a statment needs data from another function, it stacks (or piles) the new function on top of the current task. 


#### execution context & hoisting

each time a script enters a new exectution context, there are two phases of activity: 

##### prepare 
* the new scope is created. 
* variables, functions, and arguments are created. 
* the value of the this keyword is determined. 
##### execute 
* now it can assign values to variables. 
* reference function and run their code. 
* execute statements. 

#### understanding scope 
in the interpreter each execution context has it's own variables object. 
it holds the variables, function and parameters available within it. 
ecach execution context can also access it's parent's variables object. 


#### understanding errors 

if a javaScript statement generates an error, then it throws an **exception** at that point, the interpreter stops and looks for exception-handling code. 

## Error Handling & Debugging:
- If you understand (which have two) execution contexts Stages) and stacks, you will find the mistake more probable. In your code.
- Debugging is an error detecting operation. It consists of a deduction technique.
- The console helps to limit the field there's an error, but you can try identifying the particular error.
- JavaScript is packed with 7 different error forms. Everyone makes your own error object that can tell you the number of your line And the error is described.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.Use them to give your users helpful feedback.
#### Example:
![error](https://www.positronx.io/wp-content/uploads/2019/11/angular-error-handling-7253-01.png)

# JavaScript Execution Context

JavaScript is a synchronous single threaded programming language. For now, we can understand that synchronous means as, somekind of an order. And the single threaded means, executing one code line for a time.

Think you're writing a code using JavaScript and store it inside of your computer. After that, If you try to run that code, JavaScript is using a special container, a box for that process. We can introduce that container as "Execution Context".

Why this execution context is important? 'Cause, JavaScript things are happening inside of that execution context. It's like a magical box.

We can devide that execution context into 2 parts. I can introduce them like this;
  1. **Memory component**
  2. **Code component**
    
Okay, now let's try to understand what are them;

### 1. Memory component/Variable Environment 
  - You can say "Variable Environment" for this memory component.
  - Why? Because, when you run a JavaScript programm it'll store programs' variables and functions inside of this memory component. I mean "Variable Environment".

### 2. Code Component/Thread Of Execution
  - This is the place where JavaScript codes are executing.

I can show them using a table too.
| Memory Component | Code Component |
|------------------|----------------|
|                  |                |
|  variables       |                |
|                  |   Code Lines   |
|  functions       |                |
||

If you run a JavaScript program that won't run immediately. JavaScript is doing it with that execution context. So, that has 2 phases.

  i. Memory creation phase
  * In this 1st phase, javascript is trying to identify the variables inside of the execution context.
  
  ii. Code executing phase
  * This 2nd phase, is using to execute the JavaScript code lines.

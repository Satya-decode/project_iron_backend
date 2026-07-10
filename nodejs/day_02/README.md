#Js Engine and Runtime environment:-
 
 #Objective
 To understand basic concepts related to nodejs, js.

 #Topics covered - 
 - Js engine
 - V8 engine
 - Js execution
 - Node.js runtime
 - Why nodejs?
 - AST
 - Interpreter
 - Compiler
 - Parser

 # Key Points--

 1- Js engine executes code by following several checkpoints in order to safely transmission of required result-

 || Js Source code--> Parser-->AST-->Interpreter-->Compiler-->Cpu-->Response Displayed||

 2- V8 engine is being developed by GOOGLE, as it fastely execute the code , simply we can say its a type of convertor which convert JS code into machine code.

 3- We use nodejs in order to run the JS code outside the browser as it provides a runtime environment for JS raw code.

 4- Nodejs runtime environment is a type of atmosphere(software + tools + libraries) where Js code is being executed.

 # Interview notes --

 Q. What happens if parser detects a error?
 A. Whenever Parser finds an error, it will stop just at the moment because it will not generate any AST for any type of error.

 Q. Why do we need a JIT Compiler when interpreter is doing same?
 A. Jit complier is neededas it optimises the code by removing repeated functions and make it fastely executable, that's why Js is a fast executable coding language in tech industry.
 
  

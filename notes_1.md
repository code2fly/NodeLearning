# Nodejs basics - 


### What is Nodejs ?
  * nodejs is JS runtime built on top of chrome's V8 engine.
  * job of V8 or any JS engine is to take JS and compile into machine code that machine can execute.
  * V8 is written in C++, i.e. anyone could write a C++ app and integrate V8 engine
  and they could extend functionality that JS provide and that is exactly what Chrome
  or NodeJS does.
  * NodeJS is not a programming language but a runtime, the code is still in JS but the runtime provides custom functionality like tools and libraries to an env.
  also Chrome is a runtime that uses V8 to run JS code and other functionality like DOM and window are provided by the runtime (i.e. they provide same old JS but with
  custom functions and object injected).
  * Internals of Chrome & Nodejs runtime -  
  ![Internals of Chrome & Nodejs runtime](/resources/images/whats_node.PNG)


  * ***Summary - nodejs is JS on server, it is possible becoz nodejs uses V8 JS on the server to run all the JS code that we provide.
  Nodejs is able to teach JS new things by providing C++ bindings to V8, this allows JS to do anything that C++ can do like accessing Filesystem etc..***



***

### Why should you use Nodejs ??

  * Nodejs uses a event driven, non-blocking I/O ( interactions to outside world does not stop the whole process but they can work on the background while the actual main process is working)
  * the event driven basically corresponds to the even loop that takes care of the callback that can be called ones a task it is depending on completes like IO.
  * non-blocking VS blocking IO - 

  ![Non-blocking VS blocking IO](/resources/images/whys_node.PNG)


***

###
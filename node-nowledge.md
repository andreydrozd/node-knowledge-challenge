1.    What is the relationship between Node.js and V8? Can Node work without V8?

2.   How come when you declare a global variable in any Node.js file it’s not really global to all modules?

3.   When exporting the API of a Node module, why can we sometimes use exports and other times we have to use module.exports?

4.   Can we require local files without using relative paths?

5.   Can different versions of the same package be used in the same application?

6.   What is the Event Loop? Is it part of V8?

7.   What is the Call Stack? Is it part of V8?

8.   What is the difference between setImmediate and process.nextTick?

9.   How do you make an asynchronous function return a value?

10.      Can callbacks be used with promises or is it one way or the other?

11. What Node module is implemented by most other Node modules?

12.      What are the major differences between spawn, exec, and fork?

13.      How does the cluster module work? How is it different than using a load balancer?

14.      What are the --harmony-* flags?

15.      How can you read and inspect the memory usage of a Node.js process?

16.      What will Node do when both the call stack and the event loop queue are empty?

17.      What are V8 object and function templates?

18.      What is libuv and how does Node.js use it?

19.      How can you make Node’s REPL always use JavaScript strict mode?

20.     What is process.argv? What type of data does it hold?

21.      How can we do one final operation before a Node process exits? Can that operation be done asynchronously?

22.     What are some of the built-in dot commands that you can use in Node’s REPL?

23.     Besides V8 and libuv, what other external dependencies does Node have?

24.     What’s the problem with the process uncaughtException event? How is it different than the exit event?

25.     What does the _ mean inside of Node’s REPL?

26.     Do Node buffers use V8 memory? Can they be resized?

27.     What’s the difference between Buffer.alloc and Buffer.allocUnsafe?

28.     How is the slice method on buffers different from that on arrays?

29.     What is the string_decoder module useful for? How is it different than casting buffers to strings?

30.     What are the 5 major steps that the require function does?

31.      How can you check for the existence of a local module?

32.     What is the main property in package.json useful for?

33.     What are circular modular dependencies in Node and how can they be avoided?

34.     What are the 3 file extensions that will be automatically tried by the require function?

35.     When creating an http server and writing a response for a request, why is the end() function required?

36.     When is it ok to use the file system *Sync methods?

37.     How can you print only one level of a deeply nested object?

38.     What is the node-gyp package used for?

39.     The objects exports, require, and module are all globally available in every module but they are different in every module. How?

40.    If you execute a node script file that has the single line: console.log(arguments);, what exactly will node print?

41.      How can a module be both requirable by other modules and executable directly using the node command?

42.     What’s an example of a built-in stream in Node that is both readable and writable?

43.     What happens when the line cluster.fork() gets executed in a Node script?

44.     What’s the difference between using event emitters and using simple callback functions to allow for asynchronous handling of code?

45.     What is the console.time function useful for?

46.     What’s the difference between the Paused and the Flowing modes of readable streams?

47.     What does the --inspect argument do for the node command?

48.     How can you read data from a connected socket?

49.     The require function always caches the module it requires. What can you do if you need to execute the code in a required module many times?

50.     When working with streams, when do you use the pipe function and when do you use events? Can those two methods be combined?
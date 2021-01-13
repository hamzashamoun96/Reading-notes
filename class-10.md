# Error Handling & Debugging
* The JavaScript interpreter processes one line of code at a time, when a statement needs data from another function, it stacks the new function on top of the current task.
* Each time a script enters a new execution context there are two phases of activity: Prepare and Execute.
* In the interpreter, each execution context has its own variables object, It holds the variables, functions, and parameters available within it,each execution context can also access its parent's variables object. 
<hr>

### Error Objects
* Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
![ErrorObject](https://serving.photos.photobox.com/3947121759503a5ba7e6b338ee6628b0d064a713f731c45780f342f94090489b0de88d1c.jpg)
* There are two thins you can do with the errors: Debug the script to fix errors , Handle errors graceflly using the ( try, catch, finally )statements. 
* The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
* Conso1e.info() can be used for general information console.warn() can be used for warnings console.error() can be used to hold errors.
* BreakPoints can pause the execution of a script on any line using breakpoints, then you can check the values stored in variables at that point in time.
* You can create a breakpoint in your code using just the debugger keyword, when the developer tools are open, this will automatically create a breakpoint.
* Here is a common errors you might find with your scripts: Go back to basics , Missed or extra characters, Data type issues.
*  
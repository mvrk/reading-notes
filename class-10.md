## Error handling and debugging

- error objects

![image](/error%20objects.png)

- Handling exceptions
  
  >try, catch, finally

```html
try {
//Try to execute this code
catch (exception) {
//If there is an exception, run this code
finally {
//This always gets executed
```

- Throwing errors

```throw new Error('message');```
  
- debugging tips
   >Another broswer
   >add numbers
   >strip it back
   >explaining the code
   >search
   >code playgrounds
   >validation tools (JavaScript, JSON, JQUERY)

-Common errors

  >go back to basics
  >missed extra characters
  >data type issues

### Summary

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
  
- DebuggIng is the process of finding errors. It involves a process of deduction.
  
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
  
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
  
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.
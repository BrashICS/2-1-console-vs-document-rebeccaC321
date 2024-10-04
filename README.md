[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16355659)
# 2.1 - Output & the Console
###### ICS3U - Mr. Brash 🐿️

Congratulations - we wrote the [Hello World! program](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) together! If you missed that - go to [Mr. Brash's website](https://www.brash.ca/ics3/2/1).

<hr><br>

The command `console.log()` is how we write output to the _developer console_. You can put words, numbers, and more inside the brackets to have them show up on the screen. For words (characters) we need to use quotation marks:  `console.log(" ")` but for numbers we can just put the value: `console.log(3.14)`

We can also separate items with a comma (,) to print more than one thing! It will be separated by a _space_:
```JS
console.log("This","is","text.",15)    // Outputs:  This is text. 15
```

## Special Characters & Escape Sequences
Most programming languages use some special commands for things like a new line or tab (indent). These are called **_escape sequences_** and we use a backslash `\` to "escape" them.

|Sequence|Usage|
|---|---|
|`\n`|Most common - used for a **new line**.|
|`\t`|Used to insert a _horizontal_ **tab** (indent)|
|`\v`|Used to insert a _vertical_ tab|
|`\'`|Used to insert a single-quote character (apostrophe)|
|`\"`|Used to insert a double-quote character|
|`\\`|Used to insert a blackslash character|

## Console.log( )
Remember that you need to use quotes if you want to print text. 
```JS
console.log("Line 1.\nThis is \"text\"");
/* Output:
     Line 1.
     This is "text"
*/
```
One last thing - every time you use the `console.log( )` command, it automatically adds a new line (\n) at the end.

### Go check out [your task](./YOUR_TASK.md).

<br><br>

🐿️

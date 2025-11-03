try/except lets you handle errors (“exceptions”) without crashing your program. You “try” some risky code. If it fails, you move to the except block.  
### Pattern:  
{  
try:  
&nbsp;&nbsp;&nbsp;&nbsp;# risky code that might crash (like int(input()))   
except:  
&nbsp;&nbsp;&nbsp;&nbsp;# code that runs if above fails (warning, re-prompt, etc.)  
}

### Example use case:
Checking user input—convert a string to an integer. If the user enters bad data, handle it gracefully.  
{   
  while True:  
      &nbsp;&nbsp;&nbsp;&nbsp;raw = input("Enter a number: ")  
      &nbsp;&nbsp;&nbsp;&nbsp;try:  
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;num = int(raw)  
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("You entered:", num)  
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break  
      &nbsp;&nbsp;&nbsp;&nbsp;except:  
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("That's not a valid number. Try again!")  
} 

### Key points:
 - Any error in the try block jumps you into the except block.
 - Keeps your app from crashing on bad inputs or mistakes.
 - You can have multiple excepts for different error types, but a plain except: catches all errors.
 - Use it to make code robust—like user input, file access, network calls.


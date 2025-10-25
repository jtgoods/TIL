if/else in python run code whether some condition has been met, or not. 
an example of an if/else "conditional" 

x = 2   
if x > 3:   
&nbsp;&nbsp;&nbsp;&nbsp;print("x is bigger than 3")   
else:   
&nbsp;&nbsp;&nbsp;&nbsp;print("x is NOT bigger than 3")   

This will print "x is NOT bigger than 3", because the conditional after if has not been met. 

Conditional operators are as follows:  
== is “equal to”  
!= is “not equal to”  
< is “less than”  
\> is “greater than"   
<= is “less than or equal to”  
\>= is “greater than or equal to”  

an example with input: 
age = int(input("Enter your age")) 
if age >= 18: 
    print(f"you are an adult") 
else: 
    print(f"you are a minor") 


For a decision table, such as:   
| light_color |	pedestrian_waiting | outcome   
| green	      | no	               | walk   
| red	      | yes	               | stop and wait   
| yellow	  | any	               | get ready   
| any	      | any	               | check again later    

light_color = "green"  
pedestrian_waiting = "no"  
if light_color == "green" and pedestrian_waiting == "no":  
&nbsp;&nbsp;&nbsp;&nbsp;print("walk")  
elif light_color == "red" and pedestrian_waiting == "yes":  
&nbsp;&nbsp;&nbsp;&nbsp;print("stop and wait")  
elif light_color == "yellow":  
&nbsp;&nbsp;&nbsp;&nbsp;print("get ready")  
else:  
&nbsp;&nbsp;&nbsp;&nbsp;print("check again later")  

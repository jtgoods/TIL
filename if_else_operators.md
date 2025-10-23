if/else in python run code whether some condition has been met, or not.
an example of an if/else "conditional" 

x = 2
if x > 3:
    print("x is bigger than 3")
else:
    print("x is NOT bigger than 3")

this will print "x is NOT bigger than 3", because the conditional after if has not been met.

conditional operators are as follows:
== is “equal to”
!= is “not equal to”
< is “less than”
> is “greater than”
<= is “less than or equal to”
>= is “greater than or equal to”

an example with input:
age = int(input("Enter your age"))
if age >= 18:
    print(f"you are an adult")
else:
    print(f"you are a minor")

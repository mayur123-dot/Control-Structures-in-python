# Control-Structures-in-python
# Task 1
Checking if number is Even or Odd 
1) Input form the user :
   n=int(input("Enter a number: "))
   Program will prompts the user to enter an integer.
   The input will read as string.
   Then the string will converted into intger using int() function

2) Understanding Even or Odd function :
   If the number is divisible by 2 the number is Even %2==0
   If the number is not divisible by 2 then number is Odd %2!=0
   For finding the remainder the modulus operator (%) is used
      
3) Checking the condition If-Else :
   Program uses an if-else statement to check the remainder of number when divided by 2
   If the remainder is 0 then nummber is Even
   If the remainder is non 0 then number is Odd
   Program-if n % 2==0:
    print(f"{n} is an even number")
    else:
    print(f"{n} is an odd number")

4) Output the result :
   Progarm print the result based on the condition

# Task 2
Sum of integer from 1 to 50 using loop
1) Initialize a variable to store the sum :
   Before starting the loop the program creates a variable and set it to 0
   total = 0
2) Use a Loop to add number
    for x in range(1,51):
    total += x  
    A for loop is typically used to iterate through the number 1 to 50
3) Loop Execution
    The loop starts with the value 1
    The loop continues until it reaches 50
4) Output the result
    after the loop finishes the total sum is printed   

   

   
         
   

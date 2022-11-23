code:

#Calculator using pyhton language.
#code by @princeimm
#creating methods to define a calculator's operations
def add( x ,y):
        return x + y
    
def multiply(x, y):
        return x * y

def divide( x ,y):
        return x / y
    
def subtraction(x, y):
        return x - y

print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply") 
print("4.Divide")

while True:
    
      choice =input("Select choice:")
      
      if choice in  ("1" ,"2","3","4"):
            val1 = float(input("Enter the first number:"))
            val2 = float(input("Enter the second number: "))
            
            if choice =="1":
                print(val1, "+", val2, "=", add(val1,val2))
                
            elif choice == "2":
                print(val1, "-", val2, "=",subtraction(val1,val2))
                
            elif choice == "3":
                print(val1, "*", val2, "=", multiply(val1,val2))
            
            elif choice == "4":
                  print(val1, "/", val2, "=", divide(val1,val2)) 
            
            next_calc=input("lets do next calculation(yes or no):")
            
            if  next_calc =="no":
             break
         
      else:
            print("Invalid Choice")
             

              
            
                

    
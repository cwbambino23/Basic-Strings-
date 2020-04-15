                        # Basic-Strings-
                        
myString =  "PT1000122123" #Store number in a variable 
print (myString[0:2]) #Print the characters in the string 

myString =  "1000122123PT" #Store number in a variable 
print (myString[-2:]) #Print all the numbers in the string 

            #This program will give your intials when you enter your name 

firstname =  input("Enter your first name: ") #User input their first name 
middlename =  input("Enter your middle name: ") #User input their middle name 
lastname =  input("Enter your last name: ") #User input their middle name 

print ("Your intials are",firstname[0:1], middlename[0:1], lastname[0:1]) #print the the first letter in every stored variable 



            #This program will turn the lot number and it will print the country code, product code and batch number 

Lot_number = "037-00901-00027" #Store numbers in this variable (like a array)

print("Country Number", Lot_number[:3]) #Print numbers (array in the array from 0 to 3)
print("Product Number", Lot_number[4:9]) #Print numbers (array in the array from 4 to 9)
print("Batch Number", Lot_number[10:]) #Print numbers (array in the array from 10 to the enbd of the array)
Strings using python. Getting a single or group of number/characters 

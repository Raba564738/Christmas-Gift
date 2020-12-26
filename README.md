 # Merry Christmas !
 
 ### This is your Christmas Magic Gift. 

first_name = str(input("Your first name : "))
second_name = str(input("Your second name : "))

def merry_christmas(x,y):
    x = "^"
    y = " "
    for n in range(0,20,2):
        if n == 0:
            print("                ")
        print(y * (10 - int(n/2)) + (x * n) + x + y * (10 - int(n/2)))
    print("__________||_________")
    print("                     ")
    print("   Merry Christmas\n", first_name + " " + second_name, "<3")
    
    
merry_christmas(1,2)

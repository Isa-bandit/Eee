def factors(a):
    for i in range(1, a + 1):
        if a % i == 0:
            print(i)


if __name__ == "__main__":
    b = input("Your number: ")

    if b.isdigit() and int(b) > 0:
        b = int(b)
        factors(b)
    else:
        print("Please enter positive number")

4













def print_menu():
    print("1.km to miles")
    print("2.Miles to km")

def km_miles():
    km=float(input("Enter distance in km: "))
    miles=km/1.609
    print(f"{km} in miles is:{miles}")

def miles_to_km():
    miles=float(input("Enter distance in km:"))
    km=miles*1.609
    print(f"{miles} in miles is:{km}")


if __name__=="__main__":
    print_menu()
    choice=input("Enter your choice: ")
    if choice=="1":
        km_miles()
    elif choice=="2":
        miles_to_km()
    else:
        print("Invalid choice")








def multi_table(a):
    for i in range(1,11):
        print(f"{i}x{a}={i*a}")
if __name__=="__main__":
    num=input("Enter number(1-9):")
    multi_table(int(num))








from fractions import Fraction


def add(a,b):
    print(f"Result of Addition:{a+b}")

if __name__=="__main__":
    a=Fraction(input("Enter first fraction:"))
    b=Fraction(input("Enter seconf fraction:"))
    op=input("Enter operation(+,*,-,/):")
    if op=="+":
        add(a,b)
    

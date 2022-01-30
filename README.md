# addition-of-two-numbres-using-python
def addition(value1,value2):
    add=value1+value2
    return add

def main():
    print("marvellous addition application")
    no1=int(input("enter the first number"))
    no2=int(input("enter second number"))
    ret=addition(no1,no2)
    print("addition is",ret)
if __name__=="__main__":
    main()

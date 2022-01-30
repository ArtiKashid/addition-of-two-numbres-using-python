# addition-of-two-numbres-using-python
def addition(value1,value2):
  ans=value1+value2
  return ans
def main():
  no1=int(input("Enter first number:"))
  no2=int(input("Enter second number:"))
  ret=addition(no1,no2)
  print("addition is :",ret)
  
if __name__=="__main__":
  main()

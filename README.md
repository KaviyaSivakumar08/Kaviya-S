# Kaviya-S
Count the number of digits
Step1:Start
Step2:Get a number from the user
Step3:Using a while loop, get each digit of the number and increment the count each time a digit is obtained.
Step4:Display count
Step5:Stop
#code
number=int(input())
count=0
while number>0:
  count+=1
  number=number//10;
print(count)

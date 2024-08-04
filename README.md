# CIS567-integrated-lab-1
CIS567-Week 5 Assignment- GitHub Lab Repository 1
num1 = int(input())
num2 = int(input())


if num1 <= num2:
    while num1 <= num2:
        print(num1, end=' ')
        num1 += 5
    print()
else:
    print('Second integer can\'t be less than the first.')
    

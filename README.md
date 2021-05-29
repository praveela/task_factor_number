# factors of a number using while loop


n=int(input("enter the number:"))

i = 1

print("factors of %d is" %(n))

while i<=n :

    if n%i==0 :

        print(i)

    i = i+1


Output:

enter the number:12
1
2
3
4
6
12

sieve = [True] * 101
for i in range(2, 100):
    if sieve[i]:
        print(i)
        for j in range(i*i, 100, i):
            sieve[j] = False
            
            
            
            
a = 50
b = 100
 
while a !=b:
    if a > b:
        a = a - b
    else:
        b = b - a
 
print (a)
            

#Problem 8: Digit Sum

#PSUEDOCODE   

declare last,num,sum as integer 

sum = 0

input num

while num > 0

last = num % 10 

sum = sum + last

num = num \ 10

end while

print sum

end

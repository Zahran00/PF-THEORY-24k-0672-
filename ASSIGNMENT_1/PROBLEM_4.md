#Problem 4: Grocery Assistance/ Calculator

#pseudocode 

declare cash as integer 

declare done as Boolean

declare item as string

declare amount as integer

declare price as integer

declare cost as integer

declare change as integer

print "Item cash you have"

input cash

   while done = false
   
     print "Input item to buy, if no more items to buy then input Done"
     input item
        if item == "Done" then
           done = true 
        else 
           Print "please input amount of item in kgs"
           input amount 
           Print "please input price of 1 kg of the item" 
           input price 
           cost = cost + (amount * price)
       endif
      end while

change = cash - cost

print "Change Mr.bhoola will receive" 

print change 

end

![image](https://github.com/user-attachments/assets/bf6be7ed-6a3e-452e-a73e-9af8bc4292d4)

![image](https://github.com/user-attachments/assets/7e906bd4-ba05-4779-8169-bd0af578f6c0)



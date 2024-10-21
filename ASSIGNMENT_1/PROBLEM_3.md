#Problem 3: Legal age of marriage in Pakistan

#pseudocode  

declare Province as string 

declare age as integer

declare gender as string

declare legal as Boolean

print "Input your Province"

input Province 

print "Input your age"

input age

print "Input your gender"

input gender

   if province = "Sindh" then
   
      if age > 17 then 
         legal = true 
         else 
         legal = false
         
   elseif province = "Punjab"
   
      if gender = "male" and age > 17 then
         legal = true 
         elseif gender = "female" and age > 15 then 
         legal = true
      else 
         legal = false
      endif
      
   endif
   
Print "You status for marriage is: " & legal

end

![image](https://github.com/user-attachments/assets/c36d47df-ad66-404c-a618-bbbe18dba482)



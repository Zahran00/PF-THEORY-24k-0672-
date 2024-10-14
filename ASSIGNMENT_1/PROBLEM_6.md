#Problem 6: Amusement Park Ride eligibility 

#Pseudocode

declare height,age as integer 

declare ride as string 

input height 

input age

input ride

if (ride == "The Dragon Roller Coaster") then
   
   if (height >= 48) and (age >= 10) then
     
     print "You meet the criteria for The Carousel."
   
     else 
   
     print "Sorry, you do not meet the criteria for The Dragon Roller Coaster."
   
     endif
elseif (ride == "The Carousel") then
   
   if (age >= 5) then
     
     print "You meet the criteria for The Carousel."
    else 
      print "Sorry, you do not meet the criteria for The Dragon Roller Coaster."
    
    endif

elseif (ride == "The Sky Swing") then
   
   if (height >= 54) then
     
     print "You meet the criteria for The Carousel."
   
   else
     
     print "Sorry, you do not meet the criteria for The Dragon Roller Coaster."
   
   endif

endif

end


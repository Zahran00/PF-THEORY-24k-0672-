#Problem 5 : Crop Management

#Psuedocode

declare crop as string

moisture, rainfall, irrigation as integer

print "input crop name"

input crop

print "input moisture level in percentage"

input moisture

print "input last time rainfall happend (in hours)" 

input rainfall

if (crop == wheat) then 

   if (moisture < 30) and (rainfall >= 24) then
      irrigation = 1 
   else 
      irrigation = 0 
   endif 

elseif (crop == corn) then

   if (moisture < 40) then 
   irrigation = 1 
   else 
   irrigation = 0 
   endif

elseif (crop == rice) then

   if (moisture < 25) and (rainfall > 24) then
   irrigation = 1 
   else 
   irrigation = 0 
   endif

endif

if (irrigation == 0) then
   print "No need of irrigation is there!"   
endif 

end




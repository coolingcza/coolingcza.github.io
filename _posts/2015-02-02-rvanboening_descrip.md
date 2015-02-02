---
title: Description for Rachel's Dinner Club Program
---
 
The DinnerClub class is instantiated with two known attributes, @restaurant and 
@total.  At instantiation it also has two empty attributes, an array named @members 
and a hash named @h, which are populated by calling class methods.

@h is populated by the add_restaurant method, which adds a key-value pair of @restaurant (key)
and @total (value).

Along with being initialization parameters, @restaurant and @total are also listed as accessor
attributes, so that they can be reassigned and other information added to @h.

@members is populated by calling the add_member method and supplying the new member's name
as an argument.

DinnerClub also includes a members method, which prints the @members array to the console.
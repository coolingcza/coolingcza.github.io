---
title: Description for Rachel's Dinner Club Program
---
 
The DinnerClub class is instantiated with two known attributes, @restaurant and 
@total.  At instantiation it also has two empty attributes, an array named @members 
and a hash named @h, which are populated by calling class methods.

```ruby
  def initialize (restaurant, total) 
    @members = []
    @h= {}
    @restaurant = restaurant
    @total = total
  end
```

@h is populated by the add_restaurant method, which adds a key-value pair of @restaurant (key)
and @total (value).

```ruby
  def add_restaurant(x, y)
    @h[@restaurant] = @total
    puts h
  end
```

Along with being initialization parameters, @restaurant and @total are also listed as accessor
attributes, so that they can be reassigned and other information added to @h.

```ruby
  attr_accessor :resturant, :total
```

@members is populated by calling the add_member method and supplying the new member's name
as an argument.

```ruby
  def add_member(member)
    @members << member
  end
```

DinnerClub also includes a members method, which prints the @members array to the console.

```ruby
  def members            #type member.members into terminal and it will show you the array.
    puts @members
  end 
```
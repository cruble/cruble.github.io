---
layout: post
title: "Coding Cliches"
date: 2015-04-05 09:57:43 -0400
comments: true
categories: "Flatiron&nbsp;School"
---

####Rewriting Cliches into Ruby 

One of the most striking things about `Ruby` is its expressiveness. A `Ruby` block of programming oftens reads with the logic and fluidity of spoken language. Which makes sense, because it was designed with the programmer in mind. 

As I learned new commands, I kept associating them with real-world scenarios like `if hungry then eat else work end`. So, I decided to translate some well-known cliches into *theoretically* working `Ruby`. 

Since I'm a beginner, some of the syntax and operations might be off, but please feel free to suggest any changes/refactoring! Have a fun cliche that might look cool in `Ruby`? Please add it into the comments. 

Thanks to my teammate Cassidy Robertson for finding and sending me a great list of cliches. 

```ruby
it_pours = "It's really coming down!"

while it_rains
  it_pours
end 
```

```ruby
lemons = []

while !lemons.empty
  make_lemonade
end 

def make_lemonade 
  puts "Take lemon. Squeeze. Add water. Add sugar. Drink. Be refreshed."
end
```

```ruby
what_goes_around = what_comes_around
```

```ruby
wounds = []
healed_wounds = []

if !wounds.empty
  healed_wounds << wounds.map do { | wound | sleep(time) } 
end 
```

```ruby
case fairness 
when love
  all_is_fair = true
when war
  all_is_fair = true
end 
```
---
layout: post
title: "Coding Cliches"
date: 2015-04-05 09:57:43 -0400
comments: true
categories: "Flatiron&nbsp;School"
---

####Rewriting Cliches into Ruby 

One of the most striking things about `Ruby` is its expressiveness. Learning about loops, assignments, and conditionals, a `Ruby` command oftens reads with the logic and fluidity of regular language. I kept hearing sentences and wondering how they would translate into *theoretically* working `Ruby`. I tried to translate some well-known cliches into Ruby and, since I'm a beginner, some of the syntax might be off. If so, let me know! And feel free to suggest any refactoring. I don't mind! It's a fun exercise. 

Feel free to add your own coded clices to the comments. Also, let me know if there are any bugs in the code. 

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
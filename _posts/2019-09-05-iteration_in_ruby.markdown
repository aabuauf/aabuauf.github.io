---
layout: post
title:      "Iteration in Ruby"
date:       2019-09-05 12:18:06 +0000
permalink:  iteration_in_ruby
---


Iteration is one of the most powerful tool in ruby. Although I do programing 10 years ago using VBA, some Java and Javascript but I didn’t use iteration before. 

The school gave us sample of iteration such as each, map and collect. There are many ways of iteration. I made those samples for myself to keep using them.

**1- Select**
Very useful when you need to filter multiple values.
`[1, 2, 3, 4].select { |e| e % 2 == 0 } # returns [2, 4]`

**2- Reject**
It is !select
`[1, 2, 3, 4].reject { |e| e % 2 == 0 } # returns [1, 3]`

**3- partition**
It is select and reject
`[2, 3, 4, 5].partition { |e| e.even? } # returns [[2, 4], [3, 5]]`

**4-find**
Very useful when you need to find a single value.
`[4, 6, 8, 13].find { |e| e > 7 } # Returns 8 (the first found element)`
 
**5-all?**
`[2, 4, 6].all? { |e| e.even? } # returns true`
 
**6-any?**
`[3, 8, 42].any? { |e| e > 10 } # returns true`

I hope this inforamation is  usefull for all.

refrence: http://jeromedalbert.com/ruby-how-to-iterate-the-right-way/


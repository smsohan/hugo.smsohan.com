---
layout: post
title: "“Ah, how good it is to be among people who are reading.”"
date: 2019-04-11
comments: true
categories: ['Software Development']
---

> Rainer Maria Rilke

All creators take a deep interest in the creations of others. All
filmmakers watch a lot of movies, all good writers are also the most
prolific readers, all artists can talk at length about the smallest
pieces of art they have seen.

We, software developers, if we want to claim ourselves as the artists of
this craft, we must be prolific readers of code. There's been no better
time as today. We have immediate access to millions of lines of carefully
written code out there in the internet. Just like artists of any craft,
I've had so much fun spending time with my fellow developers that read
code for the pure joy of learning something new.

Just had so much fun reading [this ruby](https://github.com/rails/rails/blob/master/activesupport/lib/active_support/core_ext/array/inquiry.rb)
code today from the Ruby on Rails project:

```ruby
class Array
  # Wraps the array in an +ArrayInquirer+ object, which gives a friendlier way
  # to check its string-like contents.
  #
  #   pets = [:cat, :dog].inquiry
  #
  #   pets.cat?     # => true
  #   pets.ferret?  # => false
  #
  #   pets.any?(:cat, :ferret)  # => true
  #   pets.any?(:ferret, :alligator)  # => false
  def inquiry
    ActiveSupport::ArrayInquirer.new(self)
  end
end
```

The beautify of this rich API is an art. I love it. You may have
different opinions. But I hope you find your love of art in code.
There's plenty of art in code out there for everyone to enjoy.

---
layout: post
title:      "Object Lifecycle"
date:       2019-09-10 21:08:51 -0400
permalink:  object_lifecycle
---


Something I have struggled with in understanding this concept was initialization which is whenever Ruby creates a new object, it looks for a method named initialize and executes it. So one simple thing we can do is use an initialize method to put default values into all the instance variables.


For example:

We can define an initialize method that takes in an argument of a dog's breed and sets a @breed variable equal to that argument.


class Dog
  def initialize(breed)
    @breed = breed
  end
 
  def breed=(breed)
    @breed = breed
  end
 
  def breed
    @breed
  end
end

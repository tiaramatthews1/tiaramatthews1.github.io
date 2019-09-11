---
layout: post
title:      "Object Models"
date:       2019-09-11 01:25:08 +0000
permalink:  object_models
---


Something I found interesting that wasnt discussed in the Learn Curriculum was ancestors which is a method that returns an array that represents the ancestor chain. The ancestor chain is the representation of the class hierarchy in Ruby which was also new to me. 

Object class Hierarchy is the default root class in Ruby. this means that any new class inherit from object by default. 

For example:

class Child
end

Child.superclass
 => Object
 
 If we call ancestors method on object it will return the following ancestor chain:
 
 irb> Object.ancestors
 => [Object, Kernel, BasicObject]

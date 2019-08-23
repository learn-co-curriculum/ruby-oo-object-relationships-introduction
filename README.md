# Introduction to Object Relationships in Ruby

So far, we've mainly worked with classes that do not play well with other custom
classes. In other words, we've defined classes that create objects that do not
interact with other objects that we've created. Instead, they have methods that
allow them to operate on themselves, or operate with some of the built-in Ruby
classes.

In object-oriented programming, however, we write programs that reflect
real-world situations and environments. In the real world, different entities
are related to one another and interact with one another in various ways.

In this section we'll discuss:

* Object relationships
* Different relationships such as "belongs-to"/"has-many"
* How to use other classes and methods within another class to collaboratively
  send messages to one another
* Exposing data stored in a class variable
* The concept of a "join" class

In the next few lessons, we'll discuss how individual objects in object-oriented
Ruby can interact with one another in ways that reflect that real-world
relatedness. It's pretty hard to imagine an application without some degree of
interaction, or association, between classes or models.


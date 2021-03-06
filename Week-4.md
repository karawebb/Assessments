# Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby? How is it different or similar to functions in JavaScript?
method in Ruby is similar to JavaScript but instead starts with a "def" and concludes with an "end" and the syntax is reduced significantly

#### 2. What does it mean that a class inherits from another class? Try to explain Ruby inheritance.


[Your Answer]
a class can inherit from another class but the super normally defines the basic attributes then the defining attributes get more 'wordy' so to speak as the objects are developed, so one object can contain all the attributes a super has but can also have other defining attributes that are not shared. so similar to species in the animal kingdom, some things can both be a mammal but may not be the same species of mammal. this helps create a framework for objects to pass information but keep each object defined individually as well


[Googled Answer]

Inheritance is when a class inherits behavior from another class. The class that is inheriting behavior is called the subclass and the class it inherits from is called the superclass. We use inheritance as a way to extract common behaviors from classes that share that behavior, and move it to a superclass.


#### 3. What is rspec and what is the general process for writing tests in RSpec?

//Your Answer
rspec is a BDD unit tester or we used it as a unit tester

basic process to write the test make sure they fail and then pass, and can take all arguments

//Googled Answer
it is a testing library


#### 4. Name three possible non-inheritance relationships between ruby objects?

//Your Answer


//Googled Answer


#### 5. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
not sure what it is called but it is used in string interpolation, an object literal?
it calls the variable to print into the string and give it back.

#### 6. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

I feel good about testing, but I didnt get through the whole process of the challenges I mainly focused on the start questions so i could also reaffirm the function of class and inheritance. it is good in general to unit test so that before you build out a program you can tell if part of it is broken or wont work in a bigger application

//Your Answer

//Googled Answer


#### 7. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer

instance variable is identified with an @  and doesnt need to be further identified because it is a reference to the scope of the object it exists in, the function normally starts with initialize

//Googled Answer
Every object has its own scope.
An object’s scope is populated with instance variables, in the moment we assign something to them. And they are visible everywhere in the object, that is, in every method that the object has.
the @word associates an instance variable to the local variables name. still unsure about the normal variable?


#### 8. Ruby has a great community and tons of free resources to help you learn. Here is the long list of great resources: https://www.ruby-lang.org/en/documentation/. Below are a few popular ones:
- Interactive Ruby tutorial (http://tryruby.org/levels/1/challenges/0)
- Why's (poigniant) Guide to Ruby: comics, anecdotes, and microscopic canaries (http://poignant.guide/book/chapter-1.html)
- Ruby in 20 min (https://www.ruby-lang.org/en/documentation/quickstart/)


Choose one of these resources and go through the material (not for hours, only looking for around 10min of your time) then come back here and list a few new things you learned about Ruby.

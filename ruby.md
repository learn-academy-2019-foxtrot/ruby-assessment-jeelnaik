# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer: 
  JavaScript and Ruby both are Object-Oriented, dynamic and scripting language.
  JavaScript is a front-end programming .language
  Ruby is back-end programming language.

  Researched answer: 
  
  Similarities:
  JavaScript and Ruby are object-oriented, dynamic and general purpose scripting language which is interpreted rather than compile during runtime.
  
  Differences:
  JavaScript can be used as front-end and back-end language using the same language whereas Ruby is used as back-end programming language.
  JavaScript can be used for Full stack development due to its node.JS framework whereas Ruby can’t be used as a Full Stack.
  JavaScript has disadvantages such as not efficient for CPU intensive tasks, inconsistent, can’t able to monitor memory utilization whereas Ruby has disadvantages such as Performance, Memory hog, code readability. 



2. What is a hash?

  Your answer:
  Hash consists of key:value pair.
  ex: 
  h1 = {'tacos':10, type: 'Mexican'}
  Hashes are similar to objects in a way that it consists of key:value pair.

  Researched answer:
  A Hash is a dictionary-like collection of unique keys and their values. Also called associative arrays, they are similar to Arrays, but where an Array uses integers as its index, a Hash allows you to use any object type.
  Hashes enumerate their values in the order that the corresponding keys were inserted.


3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer:
  Rspec is used to test ruby language.
  create the following files:
  file_name.rb
  file_name_rspec.rb
  
  In the file_name_rspec.rb,
  It is mandatory to write the following lines:
  require 'rspec'
  require_relative 'file_name'
  
  run the files using : rspec file_name_rspec.rb
  If rspec is not found,
  run gem install rspec
  
  Researched answer:
  
  Create a file called file.rb and file called file_spec.rb in the same folder. Put the following into the spec file:
    require 'rspec' - searches the gem file path and grabs it.
    require_relative 'car' - gets the car, which is within the same folder.
    In the terminal, cd to the folder with the files then:
    rspec car_spec.rb


4. Name three possible relationships between objects?

  Your answer:
  is-a ex: Car object is a Vehicle objects
  has-a ex: Car has engine
  has-many ex: Owner has many Cards

  Researched answer:



5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer:
  Variable that has scope of the class is called in instance variables.
  Instance variables can be defined by '@' in ruby.

  Researched answer:
  A local variable that is defined inside one method, for example, cannot be accessed by another method. In order to get around this limitation, we can use instance variables inside our Ruby classes.
  An instance variable is a variable that is accessible in any instance method in a particular instance of a class.



6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) multiple when then statements
kind = case year
when 1850..1889 then 'Blues'
when 1890..1909 then 'Ragtime'
when 1910..1929 then 'New Orleans Jazz'
when 1930..1939 then 'Swing'
when 1940..1950 then 'Bebop'
else 'Jazz'
end

2) menthod sqrt , to get square root of a number

3)  gsub method - It allows you to replace, or substitute characters inside a string.


7. STRETCH: What are blocks, procs, and lambdas?

  Your answer:

  Researched answer:

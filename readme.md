# Introduction to Ruby!!

## Greetings & Icebreakers(10m)
- name
- where you're from
- what you do
- favorite holiday and why?

## Administrative and Logistics!
[Chat Here!](http://www.disposablechat.com/chat/intro+to+ruby%21?password=)
We'll be using the nitrous IDE so that everyone's on the same page. If you want ruby installed in your local machine. Follow the directions [here](https://pine.fm/LearnToProgram/chap_00.html)
my email: andrew.kim@ga.co


## LO's
- describe the utility of computer programming
- define the role of a REPL in programming
- list 5 common data types used in ruby and their uses
- describe what variables are and what they are used for
- describe what a method is and why they are useful
- control flow

Prior Knowledge Inventory(10m)
-	list every day uses of computer programming
Take Email for example:
- *what did the programmer think about in order to write the program for email*
- data types

Metaphor of PB&J making robot(10m)
- computer programming allows us to do simple tasks efficiently
Bringing us back to ruby basics. To learn the building blocks of your first computer programming language.

### Some Data types(10m)
- strings
- integers(FIXNUM)
- floats
- booleans
- nil

- use variables within REPL use simple methods(narrate 10m)
	- ask why we use variables?
  - everyone always thinks algebra when they see variable assignment, but it works a little differently in programming
	- set variable name = "andy"
	- set variable to a = "something"
	- set variable to the_number_ten = 10
	- speak briefly about naming convention and semantic naming
		- what are some things about this variable name that is good?
		- going forward we want to name things semantically, but not the extreme as the above example
		- do full_name in REPL, than draw diagram(variables/value chart)
			- first_name + last_name = full_name

## Break (10 m)
### Class ex-variables (20 m)
## Write your first program!(30m)
Now that we know a little bit about data types and variables, let's write our very first program. We're going to create a file called `hello.rb` in it place:

```ruby
puts "hello world"
```

Congrats! You wrote your very first program.

I guess that's great, but it doesn't really do anything. But wait, we can do more.. in time!

Let's write a distance conversion calculator.

First let's prompt the user

```ruby
puts "What length do you need converted into km?(in miles)"
```

Then we need to get the user input, we'll do this by entering a `gets.chomp` and save it to a variable.

This will actually pause the program until a user enters information. `.chomp` eliminates the new line white space that is received when the user hits enter.

Our program should now look like this:

```ruby
puts "What length do you need converted into km?(in miles)"
length = gets.chomp
```

Now we just need to manipulate the length from miles into km,can anyone help me out with that?

Awesome, now all that we need to do is display the new distance to the user

```ruby
puts "What length do you need converted into km?(in miles)"
length_in_miles = gets.chomp
length_in_km = length_in_miles / 0.62137
puts "That length in km is " + length_in_km
```

### Class ex- temp Converter(15m)
## Break(10m)

## Control Flow ()

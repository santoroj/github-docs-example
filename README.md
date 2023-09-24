# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation(')


```
# Define a person class
class Person
   # Constructor
   def initialize(name, age)
     @name = name
     @age = age
   end

   # Instance method to return a greeting
   def greeting
     "Hello, my name is #{@name} and I am #{@age} years old."
   end
end

# Create a new instance of the Person class
person1 = Person.new("Alice", 30)

# Print out the greeting
puts person1.greeting
```

- When you can you should attempt to apply syntax hightlighting to you codeblocks
  
```ruby
# Define a person class
class Person
   # Constructor
   def initialize(name, age)
     @name = name
     @age = age
   end

   # Instance method to return a greeting
   def greeting
     "Hello, my name is #{@name} and I am #{@age} years old."
   end
end

# Create a new instance of the Person class
person1 = Person.new("Alice", 30)

# Print out the greeting
puts person1.greeting
```







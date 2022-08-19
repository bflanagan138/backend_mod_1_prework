## Day 1 Questions

1. How would you print the string `"Hello World!"` to the terminal?
p "Hello World!"
1. What character is used to indicate comments in a ruby file?
#
1. Explain the difference between an integer and a float?
integer is a whole number, a float is a decimal
1. In the space below, create a variable `animal` that holds the string `"zebra"`
animal = "zebra"
1. How would you print the string `"zebra"` using the variable that you created above?
p "#{animal}"
1. What is interpolation? Use interpolation to print a sentence using the variable `animal`.
Interpolation is entering a string into a string.
p "My favorite animal is the #{zebra}."
1. What method is used to get input from a user?
gets.chomp
1. Name and describe two common string methods:
<string>.length - returns length of characters in a string
<string>.gsub - replaces all instances of that string (global substitute)

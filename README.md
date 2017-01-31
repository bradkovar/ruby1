# ruby1

print "Enter your name: "
name = gets.chomp
puts "Hello " << name
# prints "Hello #(name)"
# print "Hello " + name
# put name

print "Enter the number of cups: "
cups = gets.chomp
cups = cups.to_i
ounces = cups * 8
print "That is #(ounces) ounces"

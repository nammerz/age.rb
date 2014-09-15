age.rb
======
puts "how old are you, young grasshopper?"
age = gets.chomp.to_i

puts "Well, you're pretty old at #{age}, but in 10 years you'll be" 
puts age + 10

puts "My goodness! I'm doing the math and at 20 years you'll be"
puts age + 20

puts "whoa... make sure you buy anti wrinkle cream because at 30 you're"
puts age + 30

puts ".... should i prep for anything because at 40 years.... yeah.. you're"
puts age + 40

puts "I am in your will right? Because in 50 years I'll be sure to take the house when you're"
puts age + 50

puts "You never told me your first name, young grasshopper"
name = gets.chomp

puts "well the world should know your name so I'm gonna let them know"
10.times do
puts name
end

puts "Am i asking too many questions? I'd also like to know your last name"
last_name = gets.chomp
puts "Well #{name} #{last_name}, it has been a pleasure talking to you"

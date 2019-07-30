# Hello-world
mini projects
Program Flow exercises
The objective of these exercises is to develop your ability to use iteration and conditional logic to build reusable functions. We will be extending our get_primes example from the Program Flow notebook for testing whether much larger numbers are prime. Large primes are useful for encryption. It is too slow to test every possible factor of a large number to determine if it is prime, so we will take a different approach.
Exercise 1: mersenne_numbers¶
A Mersenne number is any number that can be written as  2p−12p−1  for some  pp . For example, 3 is a Mersenne number ( 22−122−1 ) as is 31 ( 25−125−1 ). We will see later on that it is easy to test if Mersenne numbers are prime.

Write a function that accepts an exponent  pp  and returns the corresponding Mersenne number.

def mersenne_number(p):
def mersenne_number(p):
    return ...
Mersenne numbers can only be prime if their exponent, pp, is prime. Make a list of the Mersenne numbers for all primes pp between 3 and 65 (there should be 17 of them).

Hint: It may be useful to modify the is_prime and get_primes functions from the Program Flow notebook for use in this problem.

# we can make a list like this
my_list = [0, 1, 2]
print(my_list)
# we can also make an empty list and add items to it
another_list = []
print(another_list)
​
for item in my_list:
    another_list.append(item)
​
print(another_list)
def is_prime(number):
    return ...
​
def get_primes(n_start, n_end):
    return ...
The next cell shows a dummy solution, a list of 17 sevens. Alter the next cell to make use of the functions you've defined above to create the appropriate list of Mersenne numbers.

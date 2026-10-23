answer = input("Player 1: Please insert a number (1-100): ")
answer = int(answer)

is_correct = False
try_count = 0

while try_count < 10 and is_correct == False:
    guess = int(input("Player 2: Please guess a number! "))

    if guess == answer:
        print("Player 2: YOU Won!")
        is_correct = True

    elif guess > answer:
        print("Your guess is greater than the answer.")
        try_count += 1

    else:
        print("Your guess is smaller than the answer.")
        try_count += 1

    if is_correct== False:
        print("player2: YOU LOST!")



class Person:
    def __init__(self, first_name, last_name, age):
        self.first_name = first_name
        self.last_name = last_name
        self.age = age

    def print_first_name(self):
        print("My first name is: " + self.first_name)

    def print_last_name(self):
        print("My last name is: " + self.last_name)

    def print_info(self):
        print("My full name is: " + self.first_name + " " + self.last_name)

class Student(Person):
    def __init__(self, first_name, last_name, age):
        self.first_name = first_name
        self.last_name = last_name

    def print_last_name(self):
    print("My last name is: " + self.last_name)

def print_info(self):
    print("My full name is: " + self.first_name + " " + self.last_name)


class Student(Person):
    def print_info(self):
        print("I am a student. My full name is: " + self.first_name + " " + self.last_name)

def print_last_name(self):
    print("My last name is: " + self.last_name)

def print_info(self):
    print("My full name is: " + self.first_name + " " + self.last_name)


class Student(Person):
    def print_info(self):
        print("I am a student. My full name is: " + self.first_name + " " + self.last_name)


class Teacher(Person):
    def print_info(self):
        print("I am a teacher. My full name is: " + self.first_name + " " + self.last_name)

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

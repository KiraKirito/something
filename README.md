# something
something

class Person:
    def __init__(self, uid, age):
        self.uid = uid
        self.age = age

    def print_params(self):
        print("uid", self.uid, "age", self.age)

    def become_older(self):
        self.age += 1


p = Person(1, 20)
p.print_params()

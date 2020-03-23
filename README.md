class Person:
    def __init__(self, name, age):
        self.age = age
        self.name = name
        self.age = age

    def __add__(self, other_obj):
        return self.age + other_obj.age
        return str(self.age) + other_obj.name = p11.age

    def __sub__(self, other_obj):
        return self.age - other_obj.age= p22.age

    def __str__(self):
        return "My name is {} ".format(self.name)
    def __mul__(self, other_obj):
        return self.age * other_obj.age = p33.age

    def __truediv__(self, other_obj):
        return self.age / other_obj.age = p44.age

p44 = Person()
p33 = Person()
p22 = Person()
p11 = Person()
p1 = Person("Goshko", 15)
p2 = Person("Ivan", 14)
print(p2)
p = Person("Alex", 15)
p1 = Person("Pesho", 10)
print(p /p1) 

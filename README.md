Q1. Explain Class and Object with respect to Object-Oriented Programming. Give a suitable example.
ANS:A Class is like an object constructor, or a "blueprint" for creating objects.
    EXAMPLE
    class glint:
    def welcome_msg(self):
        print("development team is good")
    liricon = glint()
    liricon.welcome_msg()
    development team is good.

Q2. Name the four pillars of OOPs.
ANS:Abstraction.
    Encapsulation.
    Inheritance.
    Polymorphism.

Q3. Explain why the __init__() function is used. Give a suitable example.
ANS:__init_()-used-for pass data
    lass glint1:
        def __init__(self,shweta_nature,pradeep_nature,ramesh_nature):
        self.shweta_nature = shweta_nature
        self.pradeep_nature = pradeep_nature
        self.ramesh_nature = ramesh_nature
        
   def return_employee_details(self):
        return self.shweta_nature,self.pradeep_nature,self.ramesh_nature
        
  liricon12 = glint1("good","best","better")
  liricon12.shweta_nature
  'good'
    
Q4. Why self is used in OOPs?
ANS:he self keyword is used to represent an instance (object) of the given class

Q5.What is inheritance? Give an example for each type of inheritance.
ANS: Inheritance is a mechanism in which one class acquires the property of another class.
  
[OOPS.md](https://github.com/Shwetakobal/OOPS-ASSIGNMENT/files/13063883/OOPS.md)

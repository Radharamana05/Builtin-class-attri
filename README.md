# Builtin-class-attri
# python program that shows the marks of students
class student:
    def __init__(self,name):
        self.name=name
        self.marks=[]
    def input_marks(self):
        for i in range(3):
            m=int(input("enter the marks of %s in subject %d:" %(self.name,i+1)))
            self.marks.append(m)
    def display(self):
        print(self.name,"got",self.marks)
s1=student("sannitha")
s2=student("sai")
s3=student("balaji")
s1.input_marks()
s2.input_marks()
s3.input_marks()
s1.display()
s2.display()
s3.display()


# output
enter the marks of sannitha in subject 1: 33
enter the marks of sannitha in subject 2: 56
enter the marks of sannitha in subject 3: 32
enter the marks of sai in subject 1: 88
enter the marks of sai in subject 2: 65
enter the marks of sai in subject 3: 45
enter the marks of balaji in subject 1: 32
enter the marks of balaji in subject 2: 90
enter the marks of balaji in subject 3: 89

sannitha got [33, 56, 32]
sai got [88, 65, 45]
balaji got [32, 90, 89]

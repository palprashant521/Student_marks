# Student_marks
To input student name and marks and receive output in decending format

student_list = []

n = int(input("How many student data do you want to enter: "))

for i in range(0,n):
    
    x = input("Enter the name of the student: ")
    y = int(input("Enter the marks of the student: "))
    
    student_list.append((y,x))
    
student_list = sorted(student_list, reverse = True)

for i in student_list:
    
    print(i[1], i[0])

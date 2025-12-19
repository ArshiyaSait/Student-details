# Student-details

name=input("Enter student name:")
roll=input("Enter roll number:")
course=input("Enter course name:")
print("\nEnter marks out of 100:\n")
s1=int(input("Subject 1:"))
s2=int(input("Subject 2:"))
s3=int(input("Subject 3:"))
s4=int(input("Subject 4:"))
s5=int(input("Subject 5:"))
total=s1+s2+s3+s4+s5
percentage=total/5
if percentage>=90:
    grade="A+"
elif percentage>=80:
    grade="A"
elif percentage>=70:
    grade="B+"
elif percentage>=60:
    grade="B"
elif percentage>=50:
    grade="C"
else:
    grade="Fail"
print("\n======STUDENT MARKSHEET======")
print("Name:",name)
print("Roll Number:",roll)
print("Course:",course)
print("-------------------------------")
print("Subject 1:",s1)
print("Subject 2:",s2)
print("Subject 3:",s3)
print("Subject 4:",s4)
print("Subject 5:",s5)
print("-------------------------------")
print("Total marks:",total)
print("Percentage:",percentage,"%")
print("Grade:",grade)
print("===============================")

OUTPUT:

Enter student name:arshiya
Enter roll number:9
Enter course name:cs

Enter marks out of 100:

Subject 1:98
Subject 2:97
Subject 3:90
Subject 4:95
Subject 5:96

======STUDENT MARKSHEET======
Name: arshiya
Roll Number: 9
Course: cs
-------------------------------
Subject 1: 98
Subject 2: 97
Subject 3: 90
Subject 4: 95
Subject 5: 96
-------------------------------
Total marks: 476
Percentage: 95.2 %
Grade: A+
===============================

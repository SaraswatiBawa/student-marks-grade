name=str(input("Enter the student name:"))
classes=int(input("Enter the class:"))
section=str(input("Enter the section:"))
marks=int(input("Enter the marks:"))

if(marks<=100 and marks>=85):
    print("grade: excellent")
elif(marks<=85 and marks>=75):
    print("grade: very good")
elif(marks<=75 and marks>=60):
    print("grade:good")
elif(marks<=60 and marks>=45):
    print("grade: pass ")
elif(marks<=45 and marks>=1):
    print("grade fail")
else:
    print("its an error")

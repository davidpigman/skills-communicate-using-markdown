# This is a H1 header
## This is a H2 header
### This is a H3 header
#### This is a H4 header
##### This is a H5 header
###### This is a H6 header

![Image of Cute Dog](https://octodex.github.com/images/yaktocat.png)

```
Bla Bla Bla agfgadfgadfgadfgqergewqrgqergqergqergqergqergqergqergqergqergqergqergqerg
```


``` python
student_scores = {
    'Harry': 88,
    'Ron': 78,
    'Hermione': 95,
    'Draco': 75,
    'Neville': 60
}

student_grades = {}

for name in student_scores:
    score = student_scores[name]
    print(f"name {name} score {score}")

    if score >= 91:
        grade = "Outstanding"
    elif score >= 81:
        grade = "Exceeds Expectations"
    elif score >= 71:
        grade = "Acceptable"
    else:
        grade = "Fail"

    student_scores[name] = grade

print (f"student_scores {student_scores}")
        
#Scores 91 - 100: Grade = "Outstanding" 
#Scores 81 - 90: Grade = "Exceeds Expectations"
#Scores 71 - 80: Grade = "Acceptable" 
#Scores 70 or lower: Grade = "Fail" 
```

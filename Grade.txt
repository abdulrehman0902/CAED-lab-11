def grade_check(marks):
    if marks >= 80:
        print("A")
    elif marks < 80 and marks >= 60:
        print("B")
    elif marks < 60 and marks >= 50:
        print("C")
    elif marks < 50 and marks >= 40:
        print("D")
    else:
        print("F")
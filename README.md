# python-quiz-march
------launch countdown------------
def countdown_launch(n):
    for i in range(n, 0, -1):
        print(i, "...",end = " ")
    print("liftoff!")
        
countdown_launch(10)

-----------has digit---------
def has_digit(word):
    for i in word:
        if i=='1' or i == '2' or i == '3' or i == '4' or i == '5' or i == '6' or i == '7' or i == '8' or i == '9' or i == '0':
            return "contains a number"
        
    return "no numbers found"
        
        
print(has_digit("frog"))
----------------trapezoid-----------
def trapezoid_area(base1, base2, height):
    return ((base1+base2)*height)/2

print(trapezoid_area(3, 4, 5))

# practice
def is_triangle(x,y,z):
    max_byun=max(x,y,z)
    byun = x+y+z - max_byun
    if byun>max_byun:
        print("삼각형입니다.")
    else:
        print("삼각형이 아닙니다.")
is_triangle(10,5,6)
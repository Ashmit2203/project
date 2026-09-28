    import math

    def area_of_circle(radius):
        return math.pi*radius*radius


    def area_of_rectangle(length,breadth):
        return length*breadth


    def area_of_square(side):
        return side**2


    def area_of_triangle(base, height):
        return 0.5*base*height


    def area_of_trapezoid(a, b, height):
        return 0.5*(a + b)*height


    def area_of_cube(side):
        return 4*side**2


    def area_of_cuboid(height, length, breadth):
        return 2*height*(length+breadth)


    def area_of_sphere(radius):
        return 4*math.pi*radius**2


    while True:
        print("--- Area Calculator ---")
        print("1. Circle")
        print("2. Rectangle")
        print("3. Square")
        print("4. Triangle")
        print("5. Trapezoid")
        print("6. Cube")
        print("7. Cuboid")
        print("8. Sphere")
        print("9. Exit")

        shape = input("Enter your shape number: ")

        if shape == "1":
               r = float(input("Radius: "))
               print("Area =", area_of_circle(r))
        
        elif shape == "2":
                  l = float(input("Length: "))
                  b = float(input("Breadth: "))
                  print("Area =", area_of_rectangle(l,b))

        elif shape == "3":
                  s = float(input("Side: "))
                  print("Area =", area_of_square(s))

        elif shape == "4":
                  b = float(input("Base: "))
                  h = float(input("Height: "))
                  print("Area =", area_of_triangle(b, h))

        elif shape == "5":
                  a = float(input("Base 1: "))
                  b = float(input("Base 2: "))
                  h = float(input("Height: "))
                  print("Area =", area_of_trapezoid(a, b, h))

        elif shape == "6":
                  s = float(input("Side: "))
                  print("Area =", area_of_cube(s))

        elif shape == "7":
                  h = float(input("Height: "))
                  l = float(input("Length: "))
                  b = float(input("Breadth: "))
                  print("Area:", area_of_cuboid(h, l, b))

        elif shape == "8":
                  r = float(input("Radius: "))
                  print("Area=", area_of_sphere(r))

        elif shape == "9":
                  print("THANKS")
                  break
    
        else:
                  print("Choice not correct, try again")
                  11
        break        

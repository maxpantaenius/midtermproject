#These are my favorite places to travel

**In no particular order:**

- *Cape Cod, MA*
- *Sedona, AZ*
- *Colorado Springs, CO*

[Sedona, Arizona](https://en.wikipedia.org/wiki/Sedona,_Arizona)

![Sedona](/Users/maxpantaenius/Downloads/sedona.jpeg)

***What I love about travel***

I love experiencing new places and learning about the history behind those locations. One of the most interesting facts I learned about Sedona is that it was at one point under water. In fact, you can find fossils on top of these mountains and on top of the Grand Canyon. 

------------------------

Here is another piece of code I wrote:

def volume_cone():
    cone_radius = float(input("Enter the cone's radius as a decimal: "))
    cone_height = float(input("Enter the cone's height as a decimal: "))
    pi = 3.14159265359
    result = pi * cone_radius * cone_radius * (cone_height/3)
    return result

def volume_cylinder():
    cylinder_radius = float(input("Enter the cylinder's radius as a decimal: "))
    cylinder_height = float(input("Enter the cylinder's height as a decimal: "))
    pi = 3.14159265359
    result = pi * cylinder_radius * cylinder_radius * cylinder_height
    return result

def volume_cube():
    cube_length = int(input("Enter the cube's length as a whole number: "))
    result = cube_length * cube_length * cube_length
    return result

print("-----------------------")
print("Shape Volume Calculator")
print("-----------------------")
print("1. Calculate volume of a cone")
print("2. Calculate volume of a cylinder")
print("3. Calculate volume of a cube")
print()

user_choice = input("Choose 1, 2, or 3: ")

if(user_choice == "1"):
    total = volume_cone()
elif(user_choice == "2"):
    total = volume_cylinder()
elif(user_choice == "3"):
    total = volume_cube()
else:
    print("Error: You entered a bad value. Exiting program.")
    exit()

print()
print("The volume is: " + str(total))

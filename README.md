Download Link: https://assignmentchef.com/product/solved-cse240-assignment-6
<br>
<strong>Introduction</strong>

The aim of this assignment is to have you work with Object Oriented C++ with simple inheritance.

<strong>Objectives</strong>

? Build a Point3D Class

? Build a Vector3D Class that inherits from Point3D

? Demonstrate the classes working

<strong>Outcomes:</strong>

? Creation and use of classes

? Inheritance

? Pointer use, management and manipulation

<strong>Description:</strong>

You will create two classes for this project. The first will be a basic 3D Cartesian- Coordinate that stores and X,Y,Z value and has a distance formula function to get the distance between two points.

The second class is a 3D Vector class that will do basic vector math. It will inherit from the Cartesian coordinate since both share a similar base.

<strong>Specifications</strong>

<strong>Point3D.h/.cpp</strong>

<pre>This class will be a 3D Cartesian-CoordinateProperties:</pre>

? double x,y,z Method:

? Constructor taking in x,y,z

? Getters and Setters

double GetDistance(Point3D*)

<strong>Vector3D.h/.cpp</strong>

This class <strong>inherits</strong> from Point3D since it also contains: X,Y,Z values and requires a distance formula.

<pre>Further Properties:</pre>

? double size – the size of the vector

? double ux,uy,uz – the vector components as a unit vector

? double angle – angle in radians

<pre>Further Methods</pre>

? Vector3D(x,y,z) – Constructor that takes in X,Y,Z then calculates size, angle and unit vector

? Vector3D(p1,p2) – Constructor that takes in two Point3Ds and makes a vector from them

? private CalculateSize()

? private CalculateUnitVector()

? public Vector3D* getUnitVector()- create and return the unit vector

? public double dotProduct(Vector3D* other) – returns dot product

? public Vector3D* crossProduct(Vector3D* other) – returns cross product vector

? public Vector3D* add(Vector3D* other) – add two vectors together get a third

? public Vector3D* subtract(Vector3D* other) – subtract two vectors together get a

third

? public void scale(double value) – multiply the vector by the value, don’t forget

you might need to recalculate angle, size and unit vector components

? <em>Getters and setters</em>

? <em>Anything else you need to make these things work!</em>

<strong>Main.cpp</strong>

Create a simple program showing off <em>ALL</em> the functionality of your classes.

<strong>Extra Credit Opportunity</strong>

Overload the +, -, and * operators with add, subtract and scale functionality for the Vector3D class as described above (+3)

Overload the % operator in Point3D to return the distance between two points. (+2)

<strong>Grading of Programming Assignment</strong>

The TA will grade your program following these steps:(1) Compile the code. If it does not compile, If it does not compile you will receive a U on the <strong>Specifications</strong>in the Rubric

(2) The TA will read your program and give points based on the points allocated to each component, the readability of your code (organization of the code and comments), logic, inclusion of the required functions, and correctness of the implementations of each function.

Rubric<strong>:</strong>

<strong>What to Submit?</strong>

You are required to submit your solutions in a compressed format (.zip). Zip all files into a single zip file. Make sure your compressed file is labeled correctly – lastname_firstname6.zip.

The compressed file MUST contain the following:

? lastname_firstname_hw6.cpp (where the main is)

? lastname_Point3D.h &amp; .cpp files

? lastname_Vector3D.h &amp; .cpp files

No other files should be in the compressed folder.

If multiple submissions are made, the most recent submission will be graded, even if the assignment is submitted late.
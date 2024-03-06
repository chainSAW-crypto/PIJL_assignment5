readme:
This Java program is designed to calculate the area and volume of different shapes. It includes classes for Circle, Rectangle, Square, Sphere, Cylinder, and Pyramid. The program follows an object-oriented design, with an abstract class Shape and an interface Volume to handle the common functionalities and specific calculations for each shape.

## File Structure

1. *Main.java*: The main program file that provides a menu-driven interface for users to choose between calculating area and volume.

2. *Shape.java*: An abstract class representing a generic shape. It includes a non-abstract method showShape(String shape) and abstract methods calculateShape() and calculatePerimeter().

3. *Volume.java*: An interface with an abstract method calculateVolume() to handle volume calculations.

4. *Circle.java, Rectangle.java, Square.java, Sphere.java, Cylinder.java, Pyramid.java*: Individual files for each shape class, implementing the Shape abstract class and, where applicable, the Volume interface.

## Usage

1. Run Main.java to initiate the program.

2. Choose between calculating the area or volume.

3. Follow the prompts to input the required measurements for the chosen shape.

## Example

Suppose you want to calculate the area of a rectangle. You would choose the "Calculate Area" option, input the length and width, and the program would display the calculated area.

For volume calculations, suppose you want to find the volume of a sphere. You would choose the "Calculate Volume" option, input the radius, and the program would display the calculated volume.

## Coding Guidelines

- Each operation is implemented as a separate function to promote modularity.
- Comment blocks are included to explain the purpose and logic of specific code sections.
- Input validations are recommended to ensure accurate calculations.

## GitHub Repository

This program is available on GitHub at [your-repository-link]. Feel free to explore the code and contribute to its improvement.

## Author

- Name: [Tanay Kende]
- PRN: [22070126092]
- Batch: [Aiml - B1]

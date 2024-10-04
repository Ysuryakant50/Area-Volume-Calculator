# Area Volume Calculator

The **Area Volume Calculator** is a Java-based application designed to calculate the area and volume of various geometric shapes. The application uses XML for storing formulas, which are used to calculate both area and volume. Users can select different shapes, input the necessary dimensions, and instantly get the area or volume along with the respective formulas.

## Features

- **Calculate Area**: Compute the area of different shapes such as circles, rectangles, squares, triangles, etc.
- **Calculate Volume**: Compute the volume of 3D shapes like spheres, cylinders, cones, etc.
- **Shape Formula Display**: Provides the formula for calculating the area and volume of each selected shape.
- **User-Friendly Input**: Users can input the necessary dimensions (e.g., radius, height, base) for the selected shape, and the calculator will return the result immediately.

## Shapes Supported

### 2D Shapes (Area)
- Circle
- Rectangle
- Square
- Triangle
- Parallelogram
- Trapezoid

### 3D Shapes (Volume)
- Sphere
- Cylinder
- Cone
- Cube
- Rectangular Prism
- Pyramid

## Technologies Used

- **Java**: Core language used for logic and calculations.
- **XML**: Used to store the formulas for each shape’s area and volume.
- **Swing/AWT (Optional)**: If the project has a GUI interface.

## How It Works

1. **Select Shape**: Choose a shape from the available list.
2. **Input Dimensions**: Input the required dimensions (e.g., radius for a circle, height for a cylinder).
3. **Display Results**: The application calculates the area or volume and displays it along with the corresponding formula.

### Example

For calculating the **area** of a circle:
- Input: Radius = 5
- Output: Area = 78.54 (Formula used: A = πr²)

For calculating the **volume** of a cylinder:
- Input: Radius = 4, Height = 10
- Output: Volume = 502.65 (Formula used: V = πr²h)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/area-volume-calculator.git

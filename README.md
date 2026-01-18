# Sierpinski Triangle Generator
A program that generates a sierpinski triangle recursively, using Turtle.
Inspired by teaching science and maths at Forskerfabrikken to grades 3 to 4 and 5 to 6.

## How to run the program (recommended)

1. Clone the repository.

2. Create a virtual environment: python -m venv venv.

3. Activate it and install dependencies: pip install -r requirements.txt.

4. Run the .ipynb notebook

## How the algorithm works

Movement: Move the turtle forward and execute turns based on the current recursion depth.

Edge Tracking: Record the current edge coordinates after each movement.

Midpoint Calculation: Calculate the mathematical midpoint between the two most recent edges.

Queue Management: Add the newly calculated midpoint to the processing queue for the next iteration.

Cleanup: Remove the previous edge coordinate to prepare for the next triangle segment.

Gradient Analysis: Evaluate the edge coordinates to determine if the gradient is negative, positive, or neutral.

Conditional Rendering: Execute one of three conditional statements to draw the triangle based on the identified gradient, ensuring the fractal expands correctly in all directions.


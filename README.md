import matplotlib.pyplot as plt

# Data points
x_values = [-4.6, -3.6, -2.7, -2, -1.3, -0.8, 0, 0.08, 1.3, 1.8]
y_values = [0.0452, 0.0349, 0.0263, -0.0194, 0.0124, 0.0078, 0, 0.0078, 0.0132, 0.0175]

# Create the line graph
plt.figure(figsize=(8, 6))
plt.plot(x_values, y_values, marker='o', linestyle='-', color='b')

# Add labels and title
plt.xlabel('X values')
plt.ylabel('Y values')
plt.title('Line Graph of Provided Data')

# Show the graph
plt.grid(True)
plt.show()

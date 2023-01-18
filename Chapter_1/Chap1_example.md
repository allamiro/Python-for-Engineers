
```
import matplotlib.pyplot as plt

# Initialize variables
g = 9.81 # acceleration due to gravity (m/s^2)
t = 0 # starting time (s)
v = 0 # starting velocity (m/s)
dt = 0.1 # time step (s)

# Create empty lists to store data
times = []
speeds = []

# Perform calculations for each time step
while t <= 10:
    v += g * dt # update velocity
    t += dt # update time

    # Append data to lists
    times.append(t)
    speeds.append(v)

# Plot data
plt.plot(times, speeds)
plt.xlabel('Time (s)')
plt.ylabel('Speed (m/s)')
plt.show()
```

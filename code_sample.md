# Code Sample

This is a code sample written by me. It calculates the final position of an object.

### Python
initial_position = float(input("Enter the object's initial position: "))
initial_velocity = float(input("Enter the object's initial velocity: "))
acceleration = float(input("Enter the object's acceleration: "))
time_passed = float(input("Enter the time passed: "))

final_position = initial_position + initial_velocity * time_passed + 0.5 * (acceleration) * (time_passed) * (time_passed)

print("The final position is "+str(final_position))

[return to home page](./README.md)

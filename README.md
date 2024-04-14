# Hackrush
Team BabyCoders

Level 1: Navigating the Cartesian Plane [10 Points]
By cosine rule :
theta2 = np.arccos((x_target**2 + y_target**2 - L1**2 - L2**2)/(2*L1*L2))
and then by some basic trig:
theta1 = np.arctan2(y_target, x_target) - np.arctan2(L2 * np.sin(theta2), L1 + L2 * np.cos(theta2))

Level 2: Following the Smooth Trajectory [20 Points]

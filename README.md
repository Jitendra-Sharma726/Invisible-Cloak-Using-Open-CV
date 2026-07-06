# Invisible-Cloak-Using-Open-CV


if your cloak is blue instead of Red:

lower_blue = np.array([100,150,50])
upper_blue = np.array([140,255,255])

mask = cv2.inRange(hsv, lower_blue, upper_blue)



If your Cloak is Green:

lower_green = np.array([35,50,50])
upper_green = np.array([85,255,255])

mask = cv2.inRange(hsv, lower_green, upper_green)



# Ares-website-review
The ARES website is very interactive, well-designed, and visually appealing. I really liked the overall website and honestly did not find many things that need improvement.

However, I think a few sections could be made more informative. In the Projects section, we could provide more details about each project, such as what the project does, how it works, and its purpose. This would make it easier for visitors to understand the projects.

Similarly, in the Workshops section, more information could be provided about what was conducted during the workshops, what activities were performed, and what participants learned.

Overall, the website is already good, and I would focus mainly on adding more information by the "Read more" options rather than making major changes.

# ===== Robot Sensor =====
OBSTACLE_DISTANCE = 20

 while True:
 # sense
 distance = sensor_reading()

 #decide
 if distance > OBSTACLE_DISTANCE:
  left_motor_forward()
  right_motor_forward()

  else:
  left_motor_stop()
  right_motor_stop()

  #Turn
  left_motor_forward()
  right_motor_bacward()

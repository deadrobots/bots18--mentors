# Bot School plan:

1. Create Github account  
1. Write/run/test ‘Hello World’  
1. Commit to repo  
1. Build a two motor robot
1. Write/run/test/commit ‘drive forward a few inches’
1. Write/run/test/commit ‘drive then turn right’
1.  Write ‘timed_drive ()’ method
1.   Write ‘turn right (90 degrees)’ using timed_drive() method
1.  Write ‘drive a square()’ 
1.  Write ‘debug (message)’
1.  Re-write debug(message) using ‘wait_for_button()’
1.  Mount a servo based grabber on the front of robot
1.  Write code to pickup an empty soda can
1.  Mount a tophat sensor on front right of robot
1.  Write ‘line_follow()’ 
1.  Test on straight line
1.  Test on curving line
1.  Speed up 
1.  Modify line_follow() to stop at the soda can
1.  Write ‘line follow until crossing tape’ 
1.  Stop line follow after 20 second time out [if crossing tape not seen]
1. Rewrite using constants for port numbers
1.  Write ‘self test’ [run/test/commit assumed moving forward]
1. Create files for actions, constansts, drive, and utils
1.  Refactor to put constants in a separate file
1.  Refactor to put drive(), drive_timed(), etc. into drive.py
1. Refactor to put debug(), selftest(), etc. in utils.py
1. Refactor to put follow_line(), pickup_can(), etc. into actions.py
1. Tag this commit as "Five files"
1.  Perform code review with a mentor
1.  Write ‘move_servo_ slowly()’
1.  Write a unit test for ‘move_servo_slowly()’ for fast, slow, up, down, no change 
1. Tag as "Slow servos"
1.  Mount a touch sensor on the back of the robot [for PVC wall]
1.  Write ‘back_until_touch()’
1.  Write ‘drive_until_line()’
1.  Mount a second tophat on the front of robot
1.  Write ‘drive until squareup’ [in a new branch]
1.  Mount camera, display camera data
1.  Spin slowly, stop when red pom is seen
1.  Spin, center on red pom
1.  Find red pom, move until 6 inches away
1.  Mount claw
1.  Find red pom and grab it
1.  Calibrated drive distances
1.  While loops (time, touch, line, etc.)
1.  Threads
1.  PEP syntax checking
1.  Other sensors (accelerometer, gyroscope, etc.)

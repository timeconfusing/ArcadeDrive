# ArcadeDrive.html
An HTML webpage coded in JavaScript to demonstrate a non-clipping full stick range control for Arcade Drive.
Row headings are the speed input from the joystick and Column headings are the yaw input from the joystick. Table values are the outputs to the motors. The scale is setup for joystick range of -127 to 127 and motor values of -127 to 127. These values are taken from the arrays in JavaScript that define the heading values. The tables show intermediate steps to visualize how the values are changing.
https://timeconfusing.github.io/arcade.html

# X-ArcadeDrive.html
HTML webpage coded in JavaScript to demonstrate a non-clipping full stick range control for X-Arcade Drive.
Understanding what is happening in the Arcade Drive calculations is important before viewing X-Arcade tables. In X-Arcade, the vertical (forward-reverse) and horizontal (sideways) components are calculated first. (They are also the row and column heading from the stick values, respectively.) Then Yaw is calculated. There is no good reason for this, as driving is typically Vertical + Yaw or Horizontal or Vertical + Horizontal (diagonal). All three controls are used sparingly since Yaw is w.r.t. to the Vertical component. It is possible to add a second Yaw control w.r.t. to the Horizontal component if desired. In the webpage, Yaw is controlled by a slider. The default of 0 shows vertical and horizontal drive values. The final table showing all motor values updates automatically when the slider changes.
https://timeconfusing.github.io/x-arcade.html

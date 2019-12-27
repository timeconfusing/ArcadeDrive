# ArcadeDrive.html
An HTML webpage coded in JavaScript to demonstrate a non-clipping full stick range control for Arcade Drive.
Row headings are the speed input from the joystick and Column headings are the yaw input from the joystick. Table values are the outputs to the motors. The scale is setup for joystick range of -127 to 127 and motor values of -127 to 127. These values are taken from the arrays in JavaScript that define the heading values. The tables show intermediate steps to visualize how the values are changing.

# X-ArcadeDrive.html
HTML webpage coded in JavaScript to demonstrate a non-clipping full stick range control for X-Arcade Drive.
Understanding what is happening in the Arcade Drive calculations is important before viewing X-Arcade tables. In X-Arcade, the vertical (forward-reverse) and horizontal (sideways) components are calculated first. Then Yaw is calculated. There is no good reason for this, but driving is typically Vertical + Yaw or Horizontal. All three controls are used sparingly. Yaw is w.r.t. to the Vertical component. It is possible to add a second Yaw control w.r.t. to the Horizontal component if desired. Yaw is controlled by a slider. The default of 0 shows vertical and horizontal drive values. The final table showing all motor values updates automatically when the slider changes.

# Calculator

Android studio was used to create a simple calculator. The app depends on API 23(Marshmallow).

The calculator has two modes (1) Basic mode (2) Formula Entry mode. To switch between modes, simply click the Mode button which will allow you to alternate between the modes.
The app has a layout that arranges the display and buttons such that they make effective use of the screen space.
The app meets all the requirements for Basic Operation. In addition, the following additional features were included:
 (1)Add and implement the decimal (.) key.
 (2)Formula Entry
 (3)A toggle button for switching between formula entry and basic mode.
 
 BASIC MODE:
⚫ The app has two separate layouts for portrait and landscape views as shown in the
screenshots above.
⚫ You must press a number key to append to the current operand. A new operand is
started if the display has just been cleared or an operator was the last key pressed.
⚫ You must press an operator key to select an operation.
  ◼ Pressing two operators in a row will result in the second replacing the first
  ◼ Pressing an operator after operand –> operator–>operand will first act as though
      you pressed the = key, and then pressed the = key, and then pressed the selected
      operator with the result of the prior calculation being the first operand
  ◼ Similarly, an = key will either perform a null operation if a single operand has been
entered (e.g. 35= simply yields 35) or will perform the operation if the second
operand has been provided (e.g. 5+6= yields 11).
⚫ Press the correct button (C) to either remove the last operator or the last digit (depending
on which was pressed more recently).
⚫ Press the All-Clear button (AC) to restore the display to 0.
⚫ If an operation is invalid (e.g. division by zero), the display is reset to 0.
⚫ To go to the Formula Entry mode, use the toggle button at the top of the screen.

Example:
Since calculations are done sequentially, 5*7-8+13÷5 will result in an answer of 8.

FORMULA ENTRY MODE:
Rather than displaying a single operand at a time, an entire expression is queued, displaying as it is entered. To be calculated once = is pressed. The calculation follows the standard order of operations for operators. Since calculations follow the standard order of operations for operators, 5*7-8+13÷5 will resultin an answer of 29.6.
To return to the Basic mode, use the toggle button at the top of the screen.

NOTE: The .apk file is named 39P7APKFILE(openme).apk

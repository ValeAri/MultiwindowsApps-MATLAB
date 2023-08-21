# MultiwindowsApps-MATLAB #
A small example for showing how to pass information between a main app and a dialog box and back in MATLAB.

## Description: ##
#### MainApp: ####
* Basic Matlab application with a Parameter numeric edit field and an Estimate button.
* The Estimate button functionality includes opening a dialog box

#### Dialog App Information: ####
* The dialog box, triggered by the Estimate button, features a Coefficient numeric edit field and a Calculate button.
* Upon entering a positive value into the Coefficient numeric edit field and clicking the Calculate button, the calculated output is determined as [Coefficient value] * 2.
  * In case the Coefficient value exceeds 50, a warning alert will appear with the message: "Please be aware that the provided   value is too large: [Value of the Coefficient field]."
* The result of this calculation should be displayed in the Parameter numeric edit field within the main application.


### References: ###

1. https://www.mathworks.com/help/matlab/creating_guis/creating-multiwindow-apps-in-app-designer.html
2. https://www.youtube.com/watch?v=u0jgIWAxf0Y

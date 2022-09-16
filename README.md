# Calculator

### What it does:

Calculator is a Java and JavaFX GUI application. This app displays a basic calculator, doing basic opperations between numbers. The calculator can be turned on or off, and the user can delete numbers.

### How I built it:

- I created the GUI using Scene Builder, and named functions for each button.
- In MainController I created ActionEvent functions for each button, making sure that every computation will be correct and the screen, which is a label in Scene Builder, will display the results properly.
- There is also a '.' button, to make sure that the user will be able to use rational numbers as well.
- I had to take care of the divisions by 0 cases, which display an 'Impossible computation!' message in the command line.
- The Main class starts the application, loading Main.fxml, setting the size of the GUI, and displaying it.

### Challenges I ran into:

Creating the GUI and all the functions was easy, but I had to take care of exceptional cases, such as division by 0, negative numbers, and user mistakes, like begining a number with 0, or typing more than one computation sign. 

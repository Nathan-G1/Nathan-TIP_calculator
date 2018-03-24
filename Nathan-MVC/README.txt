 

        Nathan Getachew 
        ATR/6923/08
        SECTION 1

        
        This example consists of four classes. 
        Tip--the model, where the calculations are done
        Display--The class that gets inputs and shows outputs
        TipCalculatorController--the class that brings the Model and view together 
        Program which calls the controller class in the Main() method

         The TipCalculatorController class brings together 
         the display and the tip or model classes
         I use the constructor to instantiate the Display.
         Instantiating the Display calls its constructor
         which calls the Get input method
         Once the input is entered I can instantiate
         the Tip class and pass the values from the 
         Display class. Notice the dot notation and observe
         how the two classes interact
         

# Test Score Project
This is a program that has an input as a test score that will produce an output of a letter grade according to the scale using a compound IF-ELSE IF statement. 
````java

import javax.swing.JOptionPane; //This will allow for an input box

public class testScore{
  public static void main(String [] args){
    int testScore = 0;
    String input;
    input = JOptionPane.showInputDialog ("Please enter your test score);
    testScore = Integer.parseInt(input);

    if (testScore >= 90)
      JOptionPane.showMessageDialog(null, "Your grade is an A. " + testScore);
    else if (testScore >= 80)
      JOptionPane.showMessageDialog(null, "Your grade is a B. " + testScore);
    else if (testScore >= 70)
      JOptionPane.showMessageDialog(null, "Your grade is a C. " + testScore);
    else if (testScore >= 60)
      JOptionPane.showMessageDialog(null, "Your grade is a D. " + testScore);
    else
      JOptionPane.showMessageDialog(null, "Your grade is a F. " + testScore);

System.exit(0);
    }
}

````

This will then produce a popup asking to enter your test score which will result with a letter grade according to the grading scale. 

<b><img width="197" alt="Screenshot 2025-02-13 213741" src="https://github.com/user-attachments/assets/70c2510f-1e3c-4422-aa5c-b7370f6aa303" />

<b> <img width="200" alt="Screenshot 2025-02-13 214913" src="https://github.com/user-attachments/assets/85756b8b-e9ca-44e1-8bc2-eb65cd73d894" />


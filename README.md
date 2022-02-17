# gravitycalculator
Create a program that computes the distance an object will fall in Earth's gravity.

Original Code
```
class GravityCalculator {
    public static void main(String[] arguments) {
        double gravity = -9.81; // Earth's gravity in m/s^2
        double initialVelocity = 0.0;
        double fallingTime = 10.0;
        double initialPosition = 0.0;
        double finalPosition = 0.0;
        System.out.println("The object's position after " + fallingTime + " seconds is " + finalPosition + " m.");
    }
}
```

output 
![image](https://user-images.githubusercontent.com/99917984/154584852-f923c1ba-9c42-4819-a829-623134ebcc77.png)
modified code
```
public class gravitycalculator  {

    

        public static void main(String[] arguments) {
            double gravity = -9.81; // Earth's gravity in m/s^2
            double initialVelocity = 0.0;
            double fallingTime = 10.0;
            double initialPosition = 0.0;
            double x;

            x = (0.5 * gravity*(fallingTime*fallingTime)
                    + (initialVelocity * fallingTime) + (initialPosition));

            System.out.println("The object's position after " + fallingTime + " seconds is " + x + " m.");
        }
    }
    
    ```
    output
    
 ![image](https://user-images.githubusercontent.com/99917984/154586156-a97a8d40-8e8c-4f3f-be22-704cffb93ace.png)

  
  
  

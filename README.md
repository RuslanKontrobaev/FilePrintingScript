# File Printing Script

As parameters, the program input receives the number of printing times and an indication of where to print the contents of the selected file

The number of printing times (1st parameter) is limited to a range from 0 to 99 times, the 2nd parameter takes the values 0 and 1, which corresponds to printing on the screen and printing to a file

When the program is running, the user is asked for the name of the file from which the print will be made. When printing to a file, the name of the receiver file to which printing will be performed is additionally asked


When entering parameter values that are not included in the above ranges, the program will notify the user about this and offer to enter new correct parameter values. Also, if the user did not enter any parameters at all or skipped any of them, the program in this case will offer to enter them correctly

## Example of how the program works
### Source file
![image](https://user-images.githubusercontent.com/109802024/216769901-127ad26e-9934-488a-990b-aa17a5b6d984.png)

### The script after its execution with parameters 3 and 0, which corresponds to printing the contents of the file to the screen 3 times
![image](https://user-images.githubusercontent.com/109802024/216770013-edb6b7c1-3585-4f98-a7c8-3fd5a3b4ee9b.png)

### The script after its execution with parameters 3 and 1, which corresponds to printing the contents of the file to the file in the amount of 3 times
![image](https://user-images.githubusercontent.com/109802024/216770032-32673731-0a75-41d4-a5f9-ebf159e92904.png)

### Result file
![image](https://user-images.githubusercontent.com/109802024/216770041-578dd339-d43b-469f-8bde-5b2e9dac03f0.png)

### The scheme of the algorithm
![Схема программы](https://user-images.githubusercontent.com/109802024/216770429-7a24a37f-8f14-4b01-89a1-8d536f6a4921.jpg)

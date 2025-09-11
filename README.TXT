
### Answers to Lab 3, part II:

# Part II:

21. It starts at 00:00 because this is the default value if none is inputted.

23. 60 times. You could also just set the hours to 1 and minutes to 0.

24. ```
    NumberDisplay digit;
    digit = new NumberDisplay(10);
    ```
    
25. ```
    Rectanlge window;
    window = new Rectangle(int width, int length);
    ```

26. It asks for parameters hour and minute but creates a default clock. Only after that it calls setTime()
    which will take the parameters inputed and update the display to those parameters. By doing it in this way,
    setTime() will be able to be called whenever and not just when an object is created.

27. Because updateDisplay() is called through the setTime() method in the second constructor.

28. ```
    p1.print("document.txt", true);
    p1.print("report.pdf", false);

    int status1 = p1.getStatus(0);
    int status2 = p1.getStatus(500);
    ```

29. 

30. 

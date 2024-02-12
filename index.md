# Lab Report 2
## Part 1
ChatServer Code:

![Image](Screenshot 2024-01-29 at 3.51.37 PM.png)
![Image](Screenshot 2024-01-29 at 3.51.48 PM.png)

Not shown in screenshots but given Server file from lab 2 is used.


![Image](Screenshot 2024-01-29 at 3.49.16 PM.png)
The methods that is called is handleRequests().

The URL is a relevant arguement as all information is being inputed in the queries of the url. The method takes apart the url to find and display the inputted information.

The innitial query gets split (at &) into two arguments to disttinguish which argument is the user and which is the message. Then the two argumetns gets split again to get rid of the variables (s= and user=). 
Finally, the method checks if there are any '+' in the method (because for some reason spaces are replaced with '+') and replaces all '+' will spaces.   


![Image](Screenshot 2024-01-29 at 3.50.46 PM.png)
The methods that is called is handleRequests().

The URL is a relevant arguement as all information is being inputed in the queries of the url. The method takes apart the url to find and display the inputted information.

The innitial query gets split (at &) into two arguments to disttinguish which argument is the user and which is the message. Then the two argumetns gets split again to get rid of the variables (s= and user=). 
Finally, the method checks if there are any '+' in the method (because for some reason spaces are replaced with '+') and replaces all '+' will spaces.   

## Part 2
Absolute path to private key for SSH key for logging into `ieng6`
![Image](Screenshot 2024-01-27 at 6.40.19 PM.png)

Absolute path to the pyblic key for my SSH key for logging into `ieng6` (on `ieng6` file system)
![Image](Screenshot 2024-01-27 at 6.43.28 PM.png)

Terminal interaction logging into `ieng6` without being asked for password.
![Image](Screenshot 2024-01-27 at 6.41.43 PM.png)

## Part 3
In the last two weeks, I've learned the basics of url structures and how to read it in code. I've also learned how to ssh into a remote server as well as how to create a private key through the terminal and copy it to the server. Visual Studio Code and JUnit aren't entirely new to me since I've been using them for CSE12 PAs. 

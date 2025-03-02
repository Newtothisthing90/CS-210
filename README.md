# CS-210
This repository is for CS 210 SNHU

This project is a grocery item tracker that reads a list of purchased items from a text file, counts how often each item appears, and allows the user to search for an item, display all frequencies, or view a histogram. The program also automatically saves the frequency data in frequency.dat so results are available even after the program closes. This was designed to be user-friendly and efficient while maintaining good coding structure.

One of the things I did well in this project was implementing file handling in a way that allows the user to enter any file name instead of relying on a hardcoded file. I also made sure the menu system is clear and easy to navigate. The error handling ensures that if the file isn’t found or an invalid input is entered, the program gives useful feedback instead of crashing.

If I were to improve this project, I would work on making it more efficient for larger datasets. Right now, it stores everything in a map, which works fine for small files but may not scale well with very large input. Adding more sorting options to the frequency display could also make the output more user-friendly. Another improvement would be additional validation to prevent incorrect file formats from being processed.

One of the biggest challenges I faced was handling file paths correctly. At first, the program wouldn’t recognize certain files because of formatting issues when users pasted paths with extra characters like quotes. To fix this, I tested different ways users might enter file names and adjusted the instructions accordingly. Writing the menu system was also a bit tricky since I had to ensure each option functioned properly without conflicts. Debugging tools and online resources like Stack Overflow were very helpful when troubleshooting these issues.

The skills I used in this project will be useful in future coursework and programming tasks. File handling, user input validation, and structured data storage are all important in many types of applications. I also gained more experience in organizing code for readability and maintainability, making it easier to expand the project later if needed. This project helped reinforce my understanding of C++ and how to write efficient and user-friendly programs.



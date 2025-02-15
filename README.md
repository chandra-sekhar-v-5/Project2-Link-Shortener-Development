
Link Shortener Development

1. Project Overview
The Link Shortener Development project is a Java-based application designed to shorten long URLs 
into concise short links and expand them back to their original form. It demonstrates concepts such as hashing, 
data structures, file handling, and user interaction through a command-line interface.

2. Objectives
- Develop a Java-based URL Shortener system.
- Shorten long URLs and expand short URLs.
- Ensure uniqueness of short URLs and handle collisions.
- Implement error handling for duplicate and invalid URLs.
- Store URL mappings using file persistence.
- Provide a simple command-line interface for users.

3. Requirements
- Java Development Kit (JDK) 8 or above
- A Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans)

4. Installation
1. Clone the Repository:
   git clone https://github.com/yourusername/link-shortener.git

2. Navigate to Project Directory:
   cd link-shortener

3. Compile the Java Files:
   javac URLShortener.java LinkShortenerApp.java

4. Run the Program:
   java LinkShortenerApp

5. Usage Instructions
Menu Options:
- 1. Shorten URL: Enter a long URL to generate a short URL.
- 2. Expand URL: Enter a short URL to retrieve the original long URL.
- 3. Exit: Close the program.

Example:
Link Shortener Menu:
1. Shorten URL
2. Expand URL
3. Exit
Choose an option: 1
Enter the long URL: https://www.example.com/page1
Shortened URL: https://short.ly/abc123

Choose an option: 2
Enter the short URL: https://short.ly/abc123
Original URL: https://www.example.com/page1

6. Project Files
- URLShortener.java: Manages URL shortening, expansion, and data persistence.
- LinkShortenerApp.java: Provides a CLI interface for user interaction.
- url_mappings.txt: Stores URL mappings for persistence.

7. Code Explanation
- URLShortener Class:
  - Uses a HashMap for URL storage.
  - Implements a custom short code generator.
  - Saves and loads URL mappings using serialization.

- LinkShortenerApp Class:
  - Displays a simple menu.
  - Collects user input and processes actions.
  - Ensures proper error handling and user feedback.

8. Error Handling
- Displays errors for invalid short URLs.
- Prevents duplicate long URLs from generating multiple short codes.
- Handles file errors during data persistence.

9. Credits
- Developed by: V Chandra Sekhar
- Reviewed for: Internship Project
- Date: 15/02/2025

Happy Coding

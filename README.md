COMPANY: CodTech IT Solutions Pvt. Ltd.
NAME: Mansi Pokhriyal
INTERN ID: CT08DA549
DOMAIN: Java Programming
DURATION: 8 Weeks
MENTOR: Neela Santosh

PROJECT TITLE: Java-Based Weather Data Viewer Using REST API
Project Summary
As part of my internship program, I developed a console-based Java application titled "Java Weather Data Viewer". The goal of this mini-project was to demonstrate the integration of Java applications with external RESTful APIs, particularly focusing on fetching and displaying weather data from the internet using the OpenWeatherMap API.

This hands-on experience allowed me to understand the fundamentals of network communication in Java, including sending HTTP requests, handling API responses, and parsing JSON-formatted data to extract relevant weather details.

Technologies and Tools
Language: Java

HTTP Client: HttpURLConnection (built-in Java class)

JSON Parsing: org.json (via json-20210307.jar)

API Used: OpenWeatherMap API (real-time weather data)

Development Environment: Visual Studio Code

Execution Environment: Windows Command Prompt

How It Works
API Request Formation
The program constructs a full API URL by including the base endpoint, target city (e.g., "London"), the API key, and metric units for temperature.

Making the HTTP GET Call
Using HttpURLConnection, the application sends an HTTP GET request to the OpenWeatherMap server. If the response is successful (status code 200), the program continues.

Reading and Parsing the Response
The response is received in JSON format. It is read into a StringBuilder and parsed using the JSONObject class from the org.json library.

Extracting Weather Information
From the parsed JSON, the application extracts:

name: the city name

main.temp: current temperature

main.humidity: current humidity percentage

Displaying the Output
The extracted information is printed in a readable format on the console for the user.

Compilation and Execution
To compile and run the project from the command line:

bash
Copy
Edit
javac -cp .;json-20210307.jar WeatherClient.java
java -cp .;json-20210307.jar WeatherClient
Ensure the JSON library (json-20210307.jar) is in the same directory as your .java file.

Real-World Relevance
This project mirrors real-world use cases where applications must consume third-party APIs. Some potential scenarios include:

Weather applications that present live data on UI dashboards.

Smart IoT systems that react to weather changes.

Mobile or web backend services built in Java that depend on external data sources.

API monitoring tools for tracking external service health.

Key Takeaways
This internship task strengthened my knowledge in the following areas:

Communicating with REST APIs in Java

Parsing and manipulating JSON responses

Basic network programming (HTTP GET requests)

Handling real-time data in console applications

Error checking through response codes

Conclusion
The Java Weather Data Viewer project was a valuable part of my internship experience. It provided a strong foundation in API integration and JSON parsing using Java. The end result was a functional, modular console application capable of connecting to the internet, retrieving weather data, and presenting it in a clear format.

Would you like a polished PDF or formatted report version of this write-up as well?



You said:
DONT GIVE IN CMD FORMAT GIVE TEXT FORMAT SO THAT ALL CAN BE COPIED

ChatGPT said:
Absolutely! Here's the entire rewritten project description in plain text format for easy copy-pasting, without code blocks or CMD formatting:

COMPANY: CodTech IT Solutions Pvt. Ltd.
NAME: Mansi Pokhriyal
INTERN ID: CT08DA549
DOMAIN: Java Programming
DURATION: 8 Weeks
MENTOR: Neela Santosh

PROJECT TITLE: Java-Based Weather Data Viewer Using REST API

Project Summary
As part of my internship program, I developed a console-based Java application titled "Java Weather Data Viewer." The aim of this project was to showcase the integration of a Java application with an external RESTful API, specifically for retrieving and displaying real-time weather information using the OpenWeatherMap API.

This task provided practical exposure to how network operations work in Java, including sending HTTP requests, handling server responses, and parsing JSON-formatted data to extract and display relevant weather metrics.

Technologies and Tools Used

Programming Language: Java

HTTP Communication: HttpURLConnection (Java’s built-in library)

JSON Handling: org.json (external library included via json-20210307.jar)

API Source: OpenWeatherMap API (used for fetching live weather data)

Development Tool: Visual Studio Code (VS Code)

Execution Platform: Windows Command Prompt

How the Program Works

API URL Construction:
The application builds the full URL by combining the base endpoint with parameters like city name, API key, and unit (set to metric).

HTTP GET Request:
It uses HttpURLConnection to send a GET request to the OpenWeatherMap API server. If a valid response (HTTP status code 200) is received, it proceeds to process the response.

Reading the Response:
The server’s response in JSON format is read using BufferedReader and stored in a StringBuilder object.

Parsing the JSON:
Using the org.json library, the response string is converted into a JSONObject. Specific data points like city name, temperature, and humidity are then extracted.

Displaying the Output:
The extracted weather details are printed neatly in the console for the user to view.

Compiling and Running the Program

To compile the Java file, the org.json library (json-20210307.jar) must be included in the project directory. During compilation and execution, the classpath is set to include this external library.

Real-World Applications

This project simulates a real-world scenario where Java programs need to consume external web services. Practical applications include:

Weather dashboards for personal or commercial use

Integration into smart home or IoT systems

Backend services for mobile or web applications

Monitoring tools that track weather or environmental conditions in real-time

Key Learning Outcomes

Working with RESTful APIs in Java

Parsing and interpreting JSON responses

Implementing HTTP requests and handling status codes

Developing real-time data-driven applications

Improving debugging and exception handling skills

Conclusion

The "Java Weather Data Viewer" project was a core component of my internship and provided valuable experience in integrating Java applications with external APIs. The final application successfully retrieves weather data in real time, processes JSON responses, and displays the information in a clean and user-friendly manner through the console.

This project significantly enhanced my technical skills in Java, deepened my understanding of HTTP communication, and prepared me for more complex software development tasks involving external data sources.



#output:-


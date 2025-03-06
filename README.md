# Karolina - Portfolio

Welcome to my coding portfolio! Here you'll find a collection of my personal and group projects, showcasing my skills in software development, embedded systems, and low-level programming.

## 🚀 About Me
I am a Computer Science student with experience in a wide range of technologies, including **low-level programming**, **embedded systems**, **full-stack development**, and **hardware integration**. I’m passionate about learning and applying new skills to solve real-world problems. I started my studies with little experience in coding, but through hard work and dedication, I completed my first year with **cum laude honors**. I am now focused on maintaining these high standards and continuously expanding my knowledge to tackle new challenges. I am a strong believer that with enough dedication and passion everything can be achieved.

## 🔧 Skills & Technologies:
- **Languages:** C, C++, C#, Embedded C, Assembly
- **Embedded Systems:** ATmega, Arduino, Raspberry Pi, Linux (Kernel, Shell Scripting, System Programming)
- **Protocols:** I2C, SPI, UART
- **Tools:** GDB, Git, Visual Studio, Arduino IDE, Linux command line, Docker, Makefiles
- **Frameworks:** Azure, REST APIs
- **Concepts:** Memory Management, Debugging, Low-Level Programming, SCRUM (Agile Methodology), Continuous Integration, Version Control
- **Operating Systems:** Linux (Ubuntu, Raspberry Pi OS), Windows

## 💡 Currently Learning
I am actively learning about **Real-Time Operating Systems (RTOS)**, focusing on kernel development, task scheduling, and resource management. I am working with **Raspberry Pi** and **Linux**, gaining hands-on experience in configuring and optimizing systems for embedded applications. Additionally, I am expanding my knowledge in **Data Networks** and **Computer Networking**, including TCP/IP, network protocols, and real-time data communication. I am also diving into **VHDL** to understand digital design and FPGA programming, which complements my embedded systems background.

## 🔹 Featured Projects
Here are some of the most exciting projects I've worked on:

### 1. **[Pair project: Hangman Game in x86-64 Assembly](https://github.com/KarolinaGogolin/hangman_assebly)**
   A classic CLI Hangman game developed in **x86-64 Assembly** to learn low-level programming. This project helped me understand the basics of Assembly, memory management, and how computers execute instructions at the hardware level. This project might not seem perfect 
   for a person fluent in assembly however, the point of it was to learn the objectives listed before while diving into the Assembly language.

   **My Contributions:**
   - Functions: `clear_buffer`, `clear_incorrect_chars_arr`, `is_valid_input`, `is_valid_length`, `read_guess`, `read_secret_function`, `restart_or_exit`, `to_lower_case_function`, `update_incorrect_guesses`
   - Debugging of the code using GDB
   - Mostly dealing with user input, processing it, validating it and clearing the buffer


### 2. **[Thermometer & Pressure Sensor with ATmega](https://github.com/KarolinaGogolin/atmega_temp_press_sensors)**
   Developed an embedded system using the ATmega microcontroller and sensors to measure environmental data. The project involved sensor integration via I2C communication, firmware development in Embedded C, and serial debugging to ensure accurate readings.

   The final version of the system displays temperature data from two temperature sensors and a pressure sensor on the serial monitor. The attached photo shows the circuit that displays only one of the temperature readings due to the unavailability of 7-segment   
   displays at that time. As a workaround, I used two extra LEDs.

   By leveraging the temperature sensor's characteristics (which only increments in 0.5°C steps), I used one LED to indicate whether the temperature is an integer (LED off) or if there is a 0.5°C increment (LED on). Similarly, I used another LED to indicate whether the 
   temperature was below zero (LED on for negative temperatures, off otherwise).

   <img src="https://github.com/user-attachments/assets/952e9214-144e-482e-abb5-f3ad5a44387c" width="500" />


### 3. **[Group Project: [LoRaWeather: A Smart IoT Weather Station]]()**

This project is a Windows-based application that reads and visualizes weather data from sensors connected to The Things Network. The app features a user-friendly interface with real-time updates, scalable graphs, and a detailed display of sensor data from a specified city. It includes a SQL Server API to pull data from a database, an MQTT parser for real-time data retrieval, and Arduino code to interface with sensors. The project also includes a ready-to-host webpage for easy deployment.

Technologies used: C#, C++, SQL, MQTT, LiveCharts, and Microsoft MAUI.

   **My Contributions**:
  - Developed Arduino code to enable communication with The Things Network (TTN).
  - Designed and implemented the user interface (GUI).
  - Collaborated with a teammate to create a cohesive and user-friendly GUI.
  - Integrated the back-end with the front-end for smooth data display.


### 4. **[Group Project: Autonomous Line-Following and Obstacle-Avoiding Vehicle](https://github.com/KarolinaGogolin/portfolio/tree/main/car_demo)**

This project involved developing an autonomous vehicle capable of following a line on a surface while avoiding obstacles and handling hilly terrain. It was completed in collaboration with Electrical Engineering students, and I contributed to the coding and algorithm design alongside the other ACS (Applied Computer Science) student in my project group.

**Key Features:**
- Line-Following: The vehicle utilized IR sensors to detect and follow a predefined path, ensuring that it stayed on track during its movement.
- Obstacle Avoidance: Using ultrasonic sensors, the vehicle was able to detect obstacles in its path and take evasive actions, either by stopping or steering around the objects.
- Hill Detection: A gyroscope was integrated to allow the vehicle to detect and handle inclines or hills in the terrain, adjusting its movement accordingly to prevent stalling or tipping.

**My primary responsibility in this project was coding the behavior of the vehicle, focusing on:**
- Implementing object avoidance algorithms using the ultrasonic sensors to ensure safe navigation.
- Developing the hill-handling logic using the gyroscope to detect changes in terrain and adjusting the vehicle’s movement accordingly.

![5a20daf0-a1da-4276-9a07-3f96a2bcaf26](https://github.com/user-attachments/assets/3b2263e7-07a9-421b-bff4-eb091178c546)

Unfortunately the repository for this project no longer exists. You can find all the demo videos in the [car_demo directory](https://github.com/KarolinaGogolin/portfolio/tree/main/car_demo).

*Note: Unfortunately no videos of the car going up and down the hill exist*


## 🔮 Next in Line
I am continuously striving to enhance my skills and stay up-to-date with the latest technologies. In the near future, I am focusing on learning and developing expertise in the following areas:

- Rust: A systems programming language that emphasizes safety and performance, especially in low-level programming.
- Advanced C++: Diving deeper into modern C++ features (e.g., C++20, multithreading, design patterns) to build robust and efficient applications.
- Real-Time Operating Systems (RTOS): Gaining more expertise in real-time systems and understanding advanced scheduling and task management techniques.


## 🌐 Let's Connect
Feel free to reach out for collaborations, questions, or feedback!  
[LinkedIn](https://www.linkedin.com/in/karolina-gogolin-8a9935330/) | [Email](mailto:karolinagogolin@gmail.com)

---

Thanks for visiting my portfolio, and I look forward to connecting with you!

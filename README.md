# Pomodoro Clock

###### Technologies:
<p align="center">
<img src="https://img.icons8.com/color/75/000000/html-5.png" width="75" height="75" alt="HTML" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/css3.png" width="75" height="75" alt="CSS" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/javascript.png" width="75" height="75" alt="JavaScript" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/react-native.png" width="75" height="75" alt="React" style="margin: 10px 15px 0 15px;" />
</p>

- **HTML:** Used to structure the content and layout of the page, ensuring semantic hierarchy and accessibility.
- **CSS:** Extensively used for styling and presentation. Defines the visual appearance of HTML elements, including layout, colors, and fonts.
- **JavaScript:** Adds interactivity to the project. Manages the logic for the Pomodoro timer and updates the user interface dynamically.
- **React:** A JavaScript library for building user interfaces. Used to create reusable components and manage the application's state.

### Try It!
https://pomodoro-clock-fcc-front-dev-libs-cert.vercel.app/

### Functionality

This project provides an interactive Pomodoro Clock ideal for programmers and professionals looking to manage their time efficiently. It allows users to set session and break periods, start, pause, and reset the timer. The clock displays time remaining in mm:ss format and plays a sound when the timer reaches zero.

## Project Structure

- `public/style.css`: Contains CSS styles for the frontend layout and presentation.
- `public/index.html`: Main HTML file providing the structure of the application.
- `public/index.js`: JavaScript file containing the React components and logic for the Pomodoro Clock.
- `README.md`: Documentation file providing an overview of the project and its functionalities.

## Practical Use Case

The Pomodoro Clock can be used by anyone looking to improve time management. It's especially useful for programmers and professionals who adopt the Pomodoro Technique to enhance productivity. It can be integrated into personal blogs, educational websites, or used as a standalone application.

## Benefits

This project leverages HTML, CSS, and JavaScript, along with React, to ensure fast loading times and efficient performance. The responsive design ensures that users can access and use the Pomodoro Clock seamlessly on desktops, tablets, and mobile devices.

## Features and User Stories

- **User Story #1:** Displays an element with id="break-label" containing the string "Break Length".
- **User Story #2:** Displays an element with id="session-label" containing the string "Session Length".
- **User Story #3:** Includes clickable elements to decrement and increment break and session lengths with IDs "break-decrement", "break-increment", "session-decrement", and "session-increment".
- **User Story #4:** Allows incrementing and decrementing of break and session lengths.
- **User Story #5:** Displays a default value of 5 for the break length.
- **User Story #6:** Displays a default value of 25 for the session length.
- **User Story #7:** Shows a string indicating whether a session or break is in progress with id="timer-label".
- **User Story #8:** Displays the time remaining in mm:ss format with id="time-left".
- **User Story #9:** Includes a clickable element with id="start_stop" to start and pause the timer.
- **User Story #10:** Includes a clickable element with id="reset" to reset the timer.
- **User Story #11:** Resets the timer, break length, and session length to default values and returns time-left to its default state.
- **User Story #12:** Allows decrementing the break length with id="break-decrement", without allowing values less than 1.
- **User Story #13:** Allows incrementing the break length with id="break-increment", without allowing values greater than 60.
- **User Story #14:** Allows decrementing the session length with id="session-decrement", without allowing values less than 1.
- **User Story #15:** Allows incrementing the session length with id="session-increment", without allowing values greater than 60.
- **User Story #16:** Prevents setting break or session lengths to values less than 1 or greater than 60.
- **User Story #17:** Prevents setting the break length to values greater than 60.
- **User Story #18:** Starts, pauses, and resumes the timer with id="start_stop".
- **User Story #19:** Displays the remaining time in mm:ss format, decrementing every second.
- **User Story #20:** Pauses and resumes the timer when clicking the start/stop button.
- **User Story #21:** Resumes the timer from the point it was paused.
- **User Story #22:** Changes the label to "Break" when the session timer reaches zero and starts a break countdown.
- **User Story #23:** Starts a break countdown when the session timer reaches zero.
- **User Story #24:** Changes the label to "Session" when the break timer reaches zero and starts a session countdown.
- **User Story #25:** Starts a session countdown when the break timer reaches zero.
- **User Story #26:** Plays a sound when the timer reaches zero.
- **User Story #27:** The sound must be at least 1 second long.
- **User Story #28:** The sound must stop and reset when the reset button is clicked.

---

#### This is a FreeCodeCamp Challenge for Front End Development Libraries Certification
<p align="center">
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" width="250" height="75" alt="freeCodeCamp" style="margin: 0 15px; opacity: 0.6" />
</p>

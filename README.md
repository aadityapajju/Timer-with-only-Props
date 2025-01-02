# Timer-with-only-Props
Timer Application built using React and JavaScript. The application allows users to perform three essential actions on a timer: Start, Stop, and Reset. The implementation uses React's props exclusively, without relying on hookssuch as useState or useEffect, ensuring a purely prop-driven state management approach.

# Features:
Start Timer: Initiates the timer, displaying the elapsed time in seconds (or any desired format).
Stop Timer: Pauses the timer, freezing the elapsed time until restarted.
Reset Timer: Resets the timer to its initial state (zero or a predefined start value).

# Technical Highlights:
React Components:
The application is structured into reusable and stateless components that communicate via props.
Parent component manages the timer state and passes it down as props to child components.
Props Management:
All actions (start, stop, reset) are controlled via event handlers passed down as props.
The timer's current value is calculated and rendered based on props provided by the parent component.
No Hooks:
State management and side effects are implemented in a traditional, pre-hooks React style using parent component logic.
Styling:
The UI is kept minimal and intuitive, with clearly labeled buttons for each action and a display area for the timer value.

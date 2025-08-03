# icu_timer

A simple and responsive dual countdown timer web application featuring two simultaneous timers — designed for ICU or critical care settings where multiple timed intervals are essential in operation.

## Features

- **Two independent timers** running simultaneously with separate start and reset controls.
- Default timers set to **3 minutes** and **2 minutes**, but durations are fully **adjustable by the user**.
- Real-time countdown display with minutes and seconds.
- Visual alarm indication by changing timer background color when time is up.
- Audible alarm sound to alert when each timer finishes.
- Responsive and clean user interface designed for ease of use.

## Technologies Used

- HTML5 & CSS3 for layout and styling.
- Vanilla JavaScript for timer logic, asynchronous updates, and audio alarms.
- Simple, lightweight design to ensure quick load and easy customization.

## How to Use

1. Open the `index.html` file in a modern web browser.
2. Adjust the minutes for each timer using the input fields if needed.
3. Use the **Start** button under each timer to begin countdown independently.
4. Or use the **Start Both Timers** button to start both timers at once.
5. When a timer reaches zero, its background will turn red and an alarm sound will play.
6. Use the **Reset** button to reset a timer to the current input value.

## Potential Use Cases

- ICU or medical settings to track critical timing intervals (e.g., CPR cycles).
- Cooking or multitasking where multiple timers are needed concurrently.
- Any situation requiring simultaneous countdowns with clear visual and audio alerts.

## Future Improvements

- Add pause/resume functionality for each timer.
- Customize alarm sound options.
- Mobile-friendly enhancements for touchscreen use.
- Persist timer states across page reloads using localStorage or similar.

F1 Championship Interactive Leaderboard 

A dynamic, single-page web application built with Vanilla HTML, CSS, and JavaScript. This project serves as an interactive dashboard to track and manage Formula 1 championship standings for both drivers and constructor teams.

Technical Highlights

- This project demonstrates solid frontend development principles without reliance on external frameworks or libraries:
* State Management: Utilizes vanilla JavaScript arrays and objects to maintain and dynamically update the state of drivers and points.
* Data Persistence: Integrates the browser's localStorage API (f1_romanian_v8) to ensure that point updates and leaderboard rankings persist across browser sessions and page reloads.
- Dynamic DOM Manipulation: Employs JavaScript to dynamically render UI components (cards, lists, headers) based on the current data state, calculating team standings on-the-fly by aggregating individual driver points.
- Advanced UI/UX Design: Features a modern "glassmorphism" aesthetic using CSS backdrop-filters, custom CSS variables, CSS Grid/Flexbox layouts, and keyframe animations (floating ambient orbs, card slide-ins).

 Key Features

- Dual Views: Seamlessly switch between Driver Standings and Team (Constructor) Standings. Team points are automatically aggregated from their respective drivers.
- Interactive Point System: Users can increment, decrement, or manually input specific point values for any driver. The leaderboard instantly re-sorts itself based on the new point totals.
- Factory Reset: A built-in failsafe to wipe local storage and restore the leaderboard to its default initial state.
- Responsive & Animated: Fluid hover effects, custom scrollbars, and dynamic team-color bindings applied directly via CSS variables injected through JavaScript.

How to Run

- Since this is a client-side vanilla web application, no server setup or build tools are required.
- Clone this repository to your local machine.
- Open the index.html file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
- Interact with the points and switch tabs to see the logic in action!

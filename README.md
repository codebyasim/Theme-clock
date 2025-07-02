# Theme Clock Project

A responsive and interactive analog and digital clock built using **JavaScript**, **HTML**, and **CSS**.  
This project displays the current time and date with smoothly rotating clock hands and a digital time readout. It also features a dark/light mode toggle to enhance user experience and visual comfort.

## Features

- **Analog clock** with hour, minute, and second hands that rotate in real time.
- **Digital clock** display showing current time with AM/PM indicator (12-hour format).
- **Date display** with day of the week, month, and day number.
- **Dark mode toggle** to switch between light and dark themes instantly.
- **Smooth CSS transitions** for theme changes and hand rotations.
- Utilizes a custom `scale()` function to map time values to rotation degrees.

## How It Works

- Uses JavaScript’s `Date` API to fetch the current time every second.
- CSS `transform` properties rotate the clock hands based on scaled hour, minute, and second values.
- A toggle button switches the website between light and dark mode by adding/removing a CSS class on the `<html>` element.
- The digital clock and date are updated simultaneously to keep time and information accurate.

## Technologies Used

- JavaScript (DOM manipulation, events, timing)
- HTML5
- CSS3 (Flexbox, transforms, transitions)

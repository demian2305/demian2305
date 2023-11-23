# Microdot Sample: Temperature Indicator with Web Interface

Welcome to **Microdot Sample**, an example implementation of a temperature indicator with a web interface. This application uses a Flask server running with Micropython on an ESP32.

## File Structure

```
|-- main.py (main application)
|-- index.html (application interface)
|-- assets (directory with CSS and JS files)
    |-- css (interface styles)
        |-- style.css (style files)
    |-- js (JavaScript scripts)
        |-- data.js (script that updates the interface periodically)
```

## Description

The `main.py` file contains the main logic of the application, while `index.html` provides the user interface for viewing the temperature. The interface styles are located in the `css` directory, specifically in `style.css`. The `js` directory hosts the `data.js` script, responsible for periodically updating the interface.

## Quick Guide

1. Clone this repository into your development environment.
2. Run the `main.py` file on an ESP32 with Micropython.
3. Open a browser and access the web interface at `http://ip-address` (replace with the correct address and port).
4. Enjoy monitoring the temperature through the intuitive web interface.

I hope this implementation proves helpful, and you find inspiration for your own projects with Microdot!

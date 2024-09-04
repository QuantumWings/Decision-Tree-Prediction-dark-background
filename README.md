# Decision tree prediction - dark background

## Introduction

This project is an interactive decision tree prediction web application that predicts whether weather conditions are suitable for outdoor activities. It demonstrates the principles of the decision tree algorithm, a fundamental concept in machine learning. The application provides an intuitive visual interface so that users can easily understand the decision-making process.

Check out the demo [here](https://quantumwings.github.io/Decision-Tree-Prediction-dark-background/).

## Main functions

1. Interactive decision tree visualization
2. Instant prediction based on user input
3. Dynamic path highlighting
4. Responsive design, adaptable to different devices
5. 3D animated background effects

## Installation and Setup Guide

### Environmental requirements

- Modern web browser (supports HTML5, CSS3 and ES6+)
- Web server (optional, for local hosting)

### How to use

1. Download the entire HTML file to your computer.
2. Open the HTML file using a modern web browser.
3.No additional installation steps are required, the page will automatically load all necessary scripts and styles.

## Instructions for use

### Operation steps

1. Select weather conditions in the left control panel:
 - Weather outlook (sunny, cloudy, rainy)
 - Temperature (hot, mild, cool)
 - Humidity (high, normal)
 - Wind (yes, no)
2. Click the "Generate Forecast" button.
3. Observe the path highlighting in the decision tree visualization on the right to understand the prediction process.
4. Click the "Chart Description" button for more information.

### Example

Select the following criteria:
- Weather outlook: Sunny
- Temperature: hot
- Humidity: high
- Wind: No

Click "Generate Forecast" and observe the decision path: Weather Outlook -> Sunny -> Humidity -> High -> Not suitable for activities

## Project structure

- `index.html`: Contains all the necessary HTML, CSS and JavaScript code to build and display an interactive interface for decision tree predictions.

## Contribution Guidelines
If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request.

## Authorization information
This project is licensed under the terms of [MIT](https://opensource.org/licenses/MIT).

## Contact Information
If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other information
- This project uses D3.js for decision tree visualization
- Use GSAP to achieve smooth animation effects
- Create 3D background effects using Vanta.js
- The project design takes into account responsive layout, suitable for use on various devices

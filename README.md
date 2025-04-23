# Light Vehicle Chassis Revision App

A multiple-choice quiz application designed to help automotive students prepare for their Level 2 assessment on Removing and Replacing Light Vehicle Chassis Units and Components.

## Overview

This single-page web application provides a comprehensive revision tool covering:

- Steering Systems
- Suspension Systems
- Braking Systems
- Wheels and Tyres
- Working Safely
- General Procedures

The app features over 70 multiple-choice questions developed directly from the official curriculum (LV04 Remove and Replace Light Vehicle Chassis Units and Components - Level 2).

## Features

- **Topic Selection**: Choose to focus on specific areas or take a mixed quiz
- **Interactive Questions**: Immediate feedback with detailed explanations
- **Progress Tracking**: Visual indication of progress through each quiz
- **Performance Analysis**: End-of-quiz results with personalized feedback
- **Mobile-Friendly Design**: Works on all devices, from smartphones to desktops
- **No Dependencies**: Pure HTML, CSS, and JavaScript with no external libraries

## Hosting on GitHub Pages

This app is designed to be hosted on GitHub Pages as a completely static site:

1. Fork or clone this repository
2. Ensure the main HTML file is named `index.html`
3. Go to your repository Settings → Pages
4. Select "main" branch as the source
5. Your revision app will be published at `https://[your-username].github.io/[repo-name]/`

## Local Development

To run or modify this app locally:

1. Clone the repository: `git clone https://github.com/[your-username]/[repo-name].git`
2. Open `index.html` in any web browser
3. Make your changes to the HTML, CSS, or JavaScript
4. Refresh the browser to see your changes

## Customizing Questions

The question database is contained entirely within the `script` tag in `index.html`. To add, edit, or remove questions:

1. Locate the `questionsData` object in the JavaScript
2. Each topic (steering, suspension, etc.) has its own array of question objects
3. Each question object has the following structure:

```javascript
{
    question: "The text of the question?",
    options: [
        "Option A",
        "Option B",
        "Option C",
        "Option D"
    ],
    correctAnswer: 2,  // Index of the correct option (0-3)
    explanation: "Explanation of why this answer is correct."
}
```

## Accessibility and Browser Support

This app is designed to be accessible and works on all modern browsers including:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers on iOS and Android
- Internet Explorer 11 is not supported

## License

This project is available for educational use. Feel free to modify and distribute it for educational purposes.

## Credits

Developed for automotive education by Gary Crowhurst

# Problem Selector

## Overview
This is a simple HTML-based interface that allows users to select a programming platform between **Codeforces** and **LeetCode** for practice. It features an aesthetically pleasing UI with gradient background and smooth button interactions. Additionally, individual pages for **Codeforces** and **LeetCode** allow users to select problems based on difficulty ranges.

## Features
- **Minimalist UI**: A clean and modern look with a glassmorphism effect.
- **Platform Selection**: Users can navigate to either Codeforces or LeetCode pages.
- **Problem Filtering**: Users can specify difficulty ranges for problem selection.
- **Responsive Design**: Ensures the page looks good on different screen sizes.
- **Smooth Hover Effects**: Buttons scale up slightly when hovered.

## Technologies Used
- **HTML**: Structuring the webpage.
- **CSS**: Styling, including gradient background, glassmorphism, and transitions.
- **JavaScript**: Used for navigation and problem filtering.

## File Structure
```
/your_project_directory
│── index.html       # Main HTML file (Problem Selector UI)
│── cf.html          # Codeforces problem selector
│── leet.html        # LeetCode problem selector
│── README.md        # Documentation file
```

## Usage
1. Open `index.html` in a web browser.
2. Click on **Codeforces** or **LeetCode** buttons to navigate to the respective pages.
3. For **Codeforces** and **LeetCode**:
   - Enter the minimum and maximum difficulty range.
   - Click the **Get Problem Set** button to open the filtered problem list.
4. Start solving problems and improving your skills!

## Preview
The UI consists of a centered selection menu with a motivational quote:
- **Title**: "Select a Platform"
- **Buttons**: Codeforces (red) and LeetCode (orange)
- **Quote**: "Practice makes a man perfect"

For individual problem selectors:
- **Input Fields**: Minimum and maximum difficulty levels.
- **Button**: Redirects to a filtered problem set.

## Future Enhancements
- Fetch and display problems dynamically using APIs.
- Improve responsiveness with better CSS.
- Include animations and additional styling effects.

Happy Coding! 🚀


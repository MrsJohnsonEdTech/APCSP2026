# APCSP2026 - Student Project Showcase

Project showcase for SY25-26 AP Computer Science Principles students.

## Overview

This website showcases student projects from the AP Computer Science Principles course. Students have built games, simulations, and interactive applications using Python and CMU CS Academy.

## Pages

- **index.html** - Home page with information about the showcase and course
- **projects.html** - Interactive student project showcase with embedded games and applications
- **styles.css** - Responsive styling for all pages using school colors (red, black, and white)

## Project Categories

### Games
Students created fun and challenging games using game physics, collision detection, and interactive gameplay mechanics.

### Interactive Applications
Applications that respond to user input with visual feedback, demonstrating real-time computation and user experience design.

### Simulations
Projects that model real-world systems, testing algorithms and demonstrating computational thinking.

## Technologies Used

- **Python** - Primary programming language
- **CMU CS Academy** - Graphics and game development platform
- **HTML/CSS** - Website frontend
- **Responsive Design** - Mobile-friendly interface

## Key Skills Demonstrated

- Object-Oriented Programming
- Algorithm Design
- Event-Driven Programming
- Computational Thinking
- Testing & Debugging
- User Experience Design
- Code Organization
- Performance Optimization

## How to View

1. Open `index.html` in a web browser to access the home page
2. Navigate to `projects.html` to view and interact with student projects
3. Click on any project to play or interact with it directly

## Adding New Projects

To add new student projects:

1. Open `projects.html`
2. Add a new project block in the appropriate row section
3. Update the CMU CS Academy embed URL to match the student's project link
4. Add appropriate project title and description
5. Include control instructions if needed

Each project uses the following structure:
```html
<div class="tank-game-container">
    <div class="tank-game-header">
        <h2>Project Title</h2>
        <p>Project description</p>
    </div>
    <div class="tank-game-iframe-wrapper">
        <iframe src="CMU_ACADEMY_EMBED_URL"></iframe>
    </div>
    <div class="tank-game-controls">
        <h4>Controls/How to Play:</h4>
        <p>Control instructions or gameplay instructions</p>
    </div>
</div>
```

## Color Scheme

School colors used throughout:
- **Primary Red:** #c41e3a
- **Black:** #1a1a1a
- **White:** #ffffff
- **Accent Red:** #ff6b7a

## Responsive Design

The website is fully responsive and works on:
- Desktop browsers
- Tablets
- Mobile devices

## Future Enhancements

- Add project filtering by category
- Add student names or anonymized student identifiers
- Add project descriptions and learning outcomes
- Add navigation between projects
- Add project submission guidelines
- Create individual project detail pages

## License

Student work showcase - 2026 Academic Year

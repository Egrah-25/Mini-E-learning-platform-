LearnHub - Mini E-Learning Platform

A clean, functional e-learning platform prototype built with HTML, CSS, and JavaScript. This project demonstrates a modern web application for course management, progress tracking, and user authentication.

https://via.placeholder.com/800x400/4361ee/ffffff?text=LearnHub+E-Learning+Platform

🚀 Features

· Course Catalog: Browse available courses in an attractive grid layout
· Course Details: View detailed course information with lesson lists
· Progress Tracking: Visual progress bars and completion status
· User Authentication: Login and signup functionality
· Interactive Lessons: Mark lessons as completed with checkboxes
· Responsive Design: Works seamlessly on desktop and mobile devices
· Modern UI: Clean, professional design with smooth animations

🛠️ Technologies Used

· Frontend: HTML5, CSS3, JavaScript (ES6+)
· Styling: CSS Grid, Flexbox, CSS Custom Properties
· Icons: Unicode emojis for cross-platform compatibility
· Hosting: GitHub Pages compatible

📦 Installation & Setup

Option 1: GitHub Pages (Recommended)

1. Fork this repository or create a new one
2. Upload the index.html file to your repository
3. Enable GitHub Pages in your repository settings:
   · Go to Settings → Pages
   · Select "Deploy from a branch"
   · Choose "main" branch and "/ (root)" folder
   · Click Save
4. Your site will be live at: https://yourusername.github.io/repository-name

Option 2: Local Development

1. Clone or download this repository
2. Open index.html in your web browser
3. No build process or dependencies required!

🎯 How to Use

1. Browse Courses: View all available courses on the main page
2. View Details: Click "View Course" to see course details and lessons
3. Track Progress: Check off completed lessons to update your progress
4. User Account: Sign up or login to save your progress
5. Complete Courses: Mark entire courses as completed

📚 Sample Courses Included

· Web Development Fundamentals: HTML, CSS, JavaScript basics
· Data Science Essentials: Data analysis and visualization
· Digital Marketing Strategy: SEO, social media, and analytics

🎨 Customization

Adding New Courses

Edit the courses array in the JavaScript section:

```javascript
const courses = [
    {
        id: 4,
        title: "Your New Course",
        description: "Course description here",
        duration: "4 hours",
        lessons: 8,
        enrolled: 0,
        progress: 0,
        bannerText: "New",
        lessons: [
            { id: 1, title: "Lesson 1", duration: "15 min", completed: false },
            // ... more lessons
        ]
    }
];
```

Styling

Modify the CSS custom properties at the top of the style section:

```css
:root {
    --primary: #your-color;
    --secondary: #your-color;
    --accent: #your-color;
    /* ... more variables */
}
```

🌐 Browser Compatibility

· Chrome (recommended)
· Firefox
· Safari
· Edge
· Mobile browsers

📱 Responsive Design

The platform is fully responsive and works on:

· Desktop computers
· Tablets
· Mobile phones

🔧 Future Enhancements

Potential features to add:

· Backend integration for data persistence
· User profiles and dashboards
· Course categories and search
· Video lesson integration
· Quiz and assessment functionality
· Certificate generation
· Discussion forums
· Payment integration for premium courses

🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

📄 License

This project is open source and available under the MIT License.

🙏 Acknowledgments

Built as part of the VibeCoding Week 1 assignment to demonstrate modern web development practices using HTML, CSS, and JavaScript.

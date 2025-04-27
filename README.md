# RPBedu WebApp

The RPBedu WebApp is a centralized hub for accessing and managing educational web applications, designed to empower teachers and students. It provides a user-friendly interface to explore, add, edit, and import tools, with seamless JSON-based imports and a responsive design. Built with HTML, CSS, and JavaScript, the app supports both local and URL-based JSON imports, flexible tool management, and accessibility features.

## Features

Tool Management: Add, edit, and delete educational tools with fields for name, description, icon, status (active or coming-soon), and URL.

JSON Imports: Import tools from local JSON files or a URL, with a default JSON hosted at rpbedu-tools-list.json.

Automatic Import on Launch: Loads tools from the default JSON URL on every app launch, starting with a blank slate for flexibility.

Relaxed URL Validation: Supports coming-soon tools with invalid or missing URLs (defaults to #), while enforcing valid URLs for active tools.

Responsive Design: Mobile-friendly layout with smooth animations and a fixed navbar for easy navigation.

Export Tools: Export the tool list as a JSON file for backup or sharing.

Icon Customization: Choose from 10 Font Awesome icons with distinct color schemes for visual appeal.

Admin Interface: Dedicated section for managing tools, with validation, error alerts, and detailed import feedback.

Legal & Connect: Includes Terms of Service, Privacy Policy, and contact/feedback sections.

## Test the App

You can test the app directly from the Github page https://rpbedu02.github.io/RPBedu/

## Installation

To run the RPBedu WebApp locally or deploy it, follow these steps:

### Clone the Repository:

git clone https://github.com/rpbedu02/RPBedu.git
cd RPBedu
You can run the app locally by opening index.html in your browser

### Serve the App: 

Since the app is a static HTML/CSS/JS project, you can serve it using a local server:

 Using Python
python -m http.server 8000

Or use any web server (e.g., Node.js http-server, Nginx, Apache).

Open in Browser: Navigate to http://localhost:8000 (or the port provided by your server) to access the app.

Alternatively, deploy to a hosting service like GitHub Pages, Netlify, or Vercel for public access.

## Usage

### Explore Tools:

On launch, the app automatically imports tools from the default JSON URL.

Browse tools in the "Our Educational Tools" section, where active tools link to their URLs and coming-soon tools are disabled.

### Manage Tools:

Open the "Admin Tools Management" section to:

Add/Edit Tools: Fill out the form with tool details. Active tools require a valid URL; coming-soon tools accept any URL.

Delete Tools: Remove individual tools with a confirmation prompt.

Import Tools: Upload a JSON file or enter a URL to import tools. Invalid entries are skipped with detailed feedback.

Export Tools: Download the current tool list as a JSON file.

## License

See the LICENSE file for details.

## Contact

For support, feedback, or inquiries, reach out to us at:

Email: rpbedu01@protonmail.com

## GitHub Issues: 

Open an issue on this repository for bug reports or feature requests.

## Acknowledgments

Built with Font Awesome for icons.

Inspired by the need for accessible educational tools.

Thanks to the users for their feedback!

© 2025 RPBedu. All rights reserved.

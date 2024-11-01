# Resume Craft

Resume Craft is a straightforward, web-based tool that makes it easy to create professional resumes. Built using HTML, CSS, and JavaScript with Firebase Authentication, Resume Craft offers users a secure environment to register, log in, and build their resumes with customizable options.

## Features

- **User Authentication**: Secure login and registration system powered by Firebase Authentication, ensuring user data is protected.
- **Resume Creation**: Input fields for personal details, work experience, education, and skills, allowing users to build their resumes section by section.
- **Real-Time Preview**: Instantly view any changes, helping users to easily edit and perfect their resume.
- **PDF Export**: Save the final resume as a downloadable PDF, ready to be shared or printed.

## Project Structure

The project is organized into the following key files:

- **`index.html`**: Main HTML structure for the web app, containing layout and sections.
- **`style.css`**: CSS file for visual styling and layout.
- **`app.js`**: JavaScript for managing interactive features, like form handling.
- **`firebase-config.js`**: Firebase configuration and setup file, handling authentication.

## Getting Started

To set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/resume-craft.git
   cd resume-craft
   ```

2. **Set Up Firebase**:
   - Create a Firebase project [here](https://firebase.google.com/).
   - Enable Authentication in the Firebase Console, specifically Email/Password login.
   - Set up a Realtime Database or Firestore if you need additional data storage options.

3. **Configure Firebase**:
   - Copy your Firebase project’s configuration details and paste them into `firebase-config.js` in the appropriate format.

4. **Launch the App**:
   - Open `index.html` in your browser to start using Resume Craft locally.

## Prerequisites

- A Firebase account with a configured project.
- A basic understanding of HTML, CSS, and JavaScript.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend/Database**: Firebase Authentication for secure login

## Screenshots

*Include a couple of screenshots of the app here if desired.*

## Future Enhancements

- **Additional Templates**: Offer a variety of resume templates.
- **AI-Powered Suggestions**: Integrate an AI feature for content suggestions based on the user's job title or skills.
- **Resume Sections Customization**: Allow users to add or remove sections based on their preferences.

## License

This project is licensed under the MIT License.

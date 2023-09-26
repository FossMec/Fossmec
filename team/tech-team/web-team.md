# Web Team

You can select any of these tasks and get started with any of the frameworks.

### Level 1

**Project Description: Create a Tribute Page**

**Project Requirements:**

1. **HTML:** Create a simple HTML file to structure your page.
2. **CSS:** Apply basic CSS styles to make the page visually appealing.
3. **Content:** Choose a person, historical figure, or someone you admire and create a tribute page about them.
4. **Layout:** The page should have a title, an image of the person you're paying tribute to, a brief description or biography of the person, and possibly a list of accomplishments or interesting facts.
5. **Responsive Design:** Make sure your page is responsive, so it looks good on both desktop and mobile devices.

### Level 2

**Project Description: Basic To-Do App in React**

**Project Requirements:**

1. Create a React application.
2. Implement a form where users can add new tasks.
3. Display the list of tasks in a "Pending Tasks" section.
4. Allow users to mark tasks as "complete" and move them to a "Completed Tasks" section.
5. Implement the ability to edit or delete tasks.
6. Optionally, display the date and time when tasks are added and completed.

Here's a step-by-step guide to creating this app:

**1. Set Up Your React Project:** You can create a new React app using Create React App or set up your project manually.

**2. Create React Components:**

* **App.js:** This is your main component that will manage the state of tasks and render other components.
* **TaskForm.js:** A component for adding new tasks.
* **TaskList.js:** A component to display the list of tasks.
* **TaskItem.js:** A component representing a single task.

**3. Define State:** In the `App` component, define the state to store pending and completed tasks. Each task should have a title, status (pending/completed), and optional date/time.

**4. Implement Functionality:**

* In the `TaskForm` component, create a form to add new tasks. Handle the form submission and update the state with the new task.
* In the `TaskList` component, render the list of pending tasks and completed tasks separately.
* Create functions to mark tasks as complete, edit tasks, and delete tasks. These functions should update the state accordingly.

**5. Styling:** Style your app using CSS or a CSS framework like Bootstrap.

### Level 3

**Project Description: Full-Stack Web App with Authentication and User Management**

**Project Requirements:**

1. **Frontend:** Build the frontend using React.
2. **Backend:** Create a Node.js server with Express.js to handle backend logic.
3. **Database:** Use MongoDB for storing user data.
4. **User Authentication:** Implement user registration and login functionality.
5. **Email Verification:** Send email verification links to registered users.
6. **Forgot Password:** Implement a reset password functionality.
7. **Authorization:** Differentiate between admin and regular user roles.
8. **Additional Features:** Build features based on your chosen application type (mental health tracker, music player, etc.).

Here's a high-level roadmap:

**1. Set Up Your Project:**

* Create a new React app for the frontend.
* Create a Node.js project for the backend.
* Set up MongoDB for data storage.

**2. Frontend Development:**

* Create components for registration, login, and dashboard.
* Implement routing for different pages (e.g., registration, login, dashboard).
* Use a state management library like Redux or React Context for managing user authentication state.
* Design and style your frontend using CSS or a UI library like Material-UI.

**3. Backend Development:**

* Set up Express.js to create API routes.
* Implement routes for user registration, login, email verification, and password reset.
* Use a library like `bcrypt` to hash and store user passwords securely.
* Generate and send email verification links using a service like Nodemailer.
* Implement middleware for user authentication and authorization.
* Connect your Node.js backend to MongoDB using a library like Mongoose.

**4. User Authentication Flow:**

* Allow users to register with email and password.
* Enable user login and store tokens in cookies or local storage.
* Send verification emails with unique tokens for email confirmation.
* Create endpoints for verifying email addresses.
* Implement a "Forgot Password" feature with email notifications.

**5. User Roles and Authorization:**

* Differentiate between admin and regular user roles.
* Implement role-based authorization for routes and actions.
* Allow admins to manage user accounts if needed.

**6. Application Features:**

* Depending on your chosen application type (mental health tracker, music player, etc.), develop the core features of your app.
* Ensure that authenticated users can access their data securely.

**7. Deployment:**

* Deploy your frontend to a hosting service like Netlify or Vercel.
* Deploy your backend to a cloud platform like Heroku or AWS.
* Set up a production-ready MongoDB instance.

**8. Testing and Validation:**

* Test your application thoroughly, especially for security vulnerabilities.
* Ensure email verification and password reset flows work correctly.
* Handle edge cases gracefully.

**9. Documentation and Optimization:**

* Document your code and APIs.
* Optimize your application for performance and security.

This project combines several advanced concepts and technologies, so be prepared for a challenging but rewarding experience. Don't forget to research and learn about each aspect thoroughly,

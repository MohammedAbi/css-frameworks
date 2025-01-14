# Social Media App

This is a social media application built using **TailwindCSS** for styling. It includes three main pages: Authentication, Feed, and Profile. The app is designed with responsive UI and follows best practices for frontend development.

## Features

- **Authentication Page**:

  - Allows users to register or log in to the application.
  - Form validation for fields (Name, Email, Password).
  - Password must be at least 8 characters.

- **Feed Page**:

  - Displays posts with thumbnails.
  - Includes a search bar for posts and sort options.
  - Form to create new posts.

- **Profile Page**:
  - Displays a user’s profile image and username.
  - Lists posts made by the user.
  - Option to follow/unfollow other users.
  - Displays follower and following counts.

## Current Status

The app currently includes the following features:

- Authentication page with form validation.
- Feed page showing posts and the ability to create new ones.
- Profile page with user details, posts, and follow functionality.

Future improvements and features could include:

- User authentication logic (e.g., JWT tokens for secure login).
- Interactivity with the posts, including like and comment features.

## Getting Started

### Prerequisites

Ensure you have the following tools installed on your machine:

- **Node.js**
- **npm**
- **git**

### Setup

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/social-media-app.git

cd social-media-app
```

#### 2. Install Dependencies

Install the required dependencies by running:

```bash
npm install
```

This will install the necessary packages specified in the `package.json`, including:

- `autoprefixer`: A tool for automatically adding vendor prefixes to CSS.
- `postcss`: A tool for transforming CSS with JavaScript plugins.
- `tailwindcss`: The main CSS framework used in this project.

#### 3. Running the Application

To run the application locally, follow these steps:

1. Start the development server:

```bash
npm run dev
```

This will start TailwindCSS in development mode, watching for changes in your CSS files and outputting to `./dist/output.css`.

2. Open your browser and visit the following URL:

```
http://localhost:3000
```

The app will be accessible from there.

## Screenshots

Include any relevant screenshots of your pages for visual reference (optional).

## Credits

[Dev Bro - How to Make Responsive Navbar in Tailwind](https://www.youtube.com/watch?v=MWv5IWyjiuI)

[Tailwind CSS Cheat Sheet](https://www.creative-tim.com/twcomponents/cheatsheet/)

[Tailwind UI](https://tailwindui.com/)

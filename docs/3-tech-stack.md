# Tech Stack and Hosting Strategy

## Tools

- JavaScript, React, and Vite: Build the assignment list, input form, and dashboard.
- CSS: Make the pages readable on a phone and a computer.
- Browser storage: Save assignments in the student's browser for the first version. No account or database is needed, but data will not sync between devices.
- Browser Notification API: Show optional alerts while the app is open and the student allows notifications. In-app reminders will work without notification permission.
- Git and GitHub: Store the code and track changes.

## Hosting

I would host the static web app on GitHub Pages and deploy it from the `main` branch with GitHub Actions. Students could access it through a public link. After deployment, I would test the site on a phone and a laptop. A database and course-site integrations can come later.

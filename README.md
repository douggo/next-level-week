# Miscellaneous

An event from Rocketseat, NLW focus on creating apps with new technologies and best coding practices to level you up to the next stage. This year, we are going to create a feedback app using React.js with Typescript, Vite, PostCSS with Tailwind CSS, Phophor Icons and HeadlessUI (for accessibility).

This app presents the user with three types of feedback:

1. BUG (when an user encounters a bug in the app)
2. IDEA (when an user has an idea to improve something in the app)
3. OTHER (when an user has some kind of feedback that doesn't fall on the other categories)

On those three feedbacks, the user can take a screenshot of the current window to make things easier.

When adding the feedback, the data is sent to the server and stored in a database and an e-mail is sent to the owner to inform the app has received a new feedback. The app then asks if the user wants to write another feedback.

## Commands used

These commands were used to install all the libraries used in this project.

- **To initiate the project**
  - `npm create vite@latest`

- **To work with declarative CSS using Tailwind CSS**
  - `npm install -D tailwindcss`
  - `npx tailwindcss init`
  - `npx tailwindcss init -p`
  - `npm install -D tailwindcss postcss autoprefixer`
  - `npm install -D @tailwindcss/forms`
  - `npm install --save-dev tailwind-scrollbar`

- **To use Phosphor Icons**
  - `npm install phosphor-react`

- **To improve accessibility**
  - `npm install @headlessui/react`

- **To take a screenshot from the window**
  - `npm install html2canvas`

- **To make your app visible on your local network**
  - `npm run dev -- --host`

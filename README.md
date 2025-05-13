# LiveDocs

<div align="center">
  <img src="https://www.markaustria.com/livedocs.png" alt="LiveDocs - Real-Time Collaborative Document Editor" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [livedocs.markaustria.com](https://livedocs.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/livedocs](https://www.markaustria.com/livedocs)

## 📝 Description

Welcome to LiveDocs! An enhanced version of Google Docs that enables real-time collaboration with secure authentication, markdown editing, nested comments, live cursors, and instant notifications.

LiveDocs is a production-ready application with real-time collaboration, secure authentication, complete document management, nested comments with tagging and reactions, and flexible sharing options.

This project solves the complex challenges of collaborative document editing, including synchronization, permissions management, and real-time updates that are difficult to build from scratch.

**Technologies Used:** Next.js, TypeScript, Tailwind CSS, Shadcn UI, Clerk, Sentry, and LiveBlocks.

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Real-Time Collaborative Editing:** Multiple users can edit documents simultaneously with live cursors showing exactly what collaborators are working on. Changes are synchronized instantly across all connected clients without conflicts.

- **Nested Comments System:** A sophisticated commenting system that allows users to select text and add floating comments, tag other users, add emoji reactions, and create nested reply threads. Comments can be resolved, edited, or deleted, providing a complete collaboration workflow.

- **Permission-Based Sharing:** A flexible sharing system that allows document owners to invite specific users as either editors or viewers. The system includes email notifications when access is granted and a user interface for managing collaborator permissions.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/livedocs.git
   ```

2. Navigate into the project directory

   ```bash
   cd livedocs
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   Create a `.env.local` file in the root directory with the following variables:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret_key
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to see the project running.

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/livedocs/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/livedocs/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] AI-powered document suggestions and auto-formatting
- [ ] Advanced document version history and rollback capabilities
- [ ] Document templates and themes
- [ ] Offline editing with automatic synchronization when reconnected

### 📚 Acknowledgements

Special thanks to the creators of the technologies used in this project:

- [Next.js](https://nextjs.org/)
- [LiveBlocks](https://liveblocks.io/)
- [Clerk](https://clerk.dev/)
- [Sentry](https://sentry.io/)

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

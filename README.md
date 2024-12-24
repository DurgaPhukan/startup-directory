# Next Startup Directory

Welcome to **Next Startup Directory**, a modern web application designed to showcase and connect startups. Built with cutting-edge technologies, this platform empowers startups to gain visibility, collaborate, and thrive.

---

## 🚀 Features

- **Startup Listings**: Explore a curated list of startups.
- **User Authentication**: Secure login with GitHub OAuth.
- **Interactive Dashboard**: Manage and update startup information.
- **Rich Content Management**: Powered by Sanity for seamless content updates.
- **Responsive Design**: Tailored for all devices using Tailwind CSS.
- **Error Monitoring**: Sentry integration for robust issue tracking.

---

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) - React-based framework for server-side rendering and static site generation.
- **Backend**: [Sanity.io](https://www.sanity.io/) - Headless CMS for structured content.
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework.
- **Authentication**: GitHub OAuth for secure user authentication.
- **Error Tracking**: [Sentry](https://sentry.io/) for real-time error monitoring.

---

## ⚙️ Installation

Follow these steps to set up the project locally:

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or above)
- [Yarn](https://yarnpkg.com/) or npm

### Clone the Repository
```bash
git clone https://github.com/yourusername/next-startup-directory.git
cd next-startup-directory
```

### Install Dependencies
```bash
npm install
# or
yarn install
```

### Set Up Environment Variables
Create a `.env.local` file in the root directory and add the following variables:

```env
NEXT_PUBLIC_SANITY_PROJECT_ID=your-sanity-project-id
NEXT_PUBLIC_SANITY_DATASET=production
NEXT_PUBLIC_GITHUB_CLIENT_ID=your-github-client-id
NEXT_PUBLIC_GITHUB_REDIRECT_URI=https://your-deployment-url.vercel.app/api/auth/callback/github
SENTRY_DSN=your-sentry-dsn
```

### Run the Development Server
```bash
npm run dev

Visit [http://localhost:3000](http://localhost:3000) to view the application.

---

## 📦 Deployment

This application is optimized for deployment on [Vercel](https://vercel.com/):

1. Push your code to GitHub.
2. Connect your GitHub repository to Vercel.
3. Configure environment variables in Vercel settings.
4. Deploy your application.

---

## 🐛 Error Tracking
Errors and exceptions are tracked using Sentry. To view error logs:
1. Log in to your Sentry dashboard.
2. Navigate to the project's error monitoring section.
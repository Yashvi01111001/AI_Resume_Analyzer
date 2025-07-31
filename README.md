# AI Resume Analyzer 🚀

A smart tool that analyzes resumes against job descriptions using AI, providing ATS compatibility scores and improvement suggestions.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Puter.js Powered](https://img.shields.io/badge/Powered%20by-Puter.js-6e48aa)](https://docs.puter.com/)

## Features ✨

- **AI-Powered Analysis**: Get instant feedback on resume content
- **ATS Scoring**: See how well your resume passes applicant tracking systems
- **PDF Processing**: Upload and analyze PDF resumes
- **Job Matching**: Compare against specific job descriptions
- **Performance Tracking**: Save and review past analyses

## Tech Stack 🛠️

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Puter.js (Serverless)
- **AI**: Claude (via Puter AI)
- **PDF Processing**: pdf-lib, pdf2img
- **State Management**: Zustand


## Getting Started

### Prerequisites
- Node.js (v18+)
- Puter developer account
- Git
  

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.


# Clone the repository
git clone https://github.com/zuhayrkabir/ai-resume-analyzer.git
cd ai-resume-analyzer

---

Built with ❤️ using React Router.

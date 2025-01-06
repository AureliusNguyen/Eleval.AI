# **Eleval.AI**

**Eleval.AI** is a Next.js web application deployed on Vercel that evaluates large language models (LLMs) by testing their performance on different NLP tasks. This app provides an intuitive interface for users to submit prompts and receive detailed evaluations of LLM responses.

## **Table of Contents**

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Deployment](#deployment)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## **Features**

- Upload prompts and get structured evaluations of LLM responses.
- Compare multiple LLMs' performance side-by-side.
- Save and track evaluation results.
- Fast response and auto-scaling via Vercel.
- Supports multiple LLM APIs (OpenAI, GPT-4, Gemini, etc.).

---

## **Technologies Used**

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, API Routes
- **Deployment**: Vercel
- **Authentication**: Clerk or NextAuth
- **LLM APIs**: Groq API

---

## **Getting Started**

### **Prerequisites**

Ensure you have the following installed:

- Node.js (v18 or later)
- npm or yarn

### **Installation**

Clone the repository:

```bash
git clone https://github.com/AureliusNguyen/Eleval.AI.git
cd Eleval.AI
```

### **Install dependencies**

```bash
npm install
# or
yarn install
```

### **Running Locally**

```bash
npm run dev
# or
yarn dev
```

## **Deployment**

This app is optimized for deployment on Vercel. To deploy:
This app is optimized for deployment on Vercel. To deploy:

Link your project to Vercel using the command:

```bash
vercel link
```

Run the following to deploy:

```bash
vercel
```

## **License**

This project is licensed under the MIT License.

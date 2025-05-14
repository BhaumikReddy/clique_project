<p align="center">
  <img src="📷Clique.png" alt="Clique Banner" width="100%" />
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-brightgreen)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.x-green)](https://www.mongodb.com/)
[![Stripe](https://img.shields.io/badge/Stripe-Integrated-blue)](https://stripe.com/)
[![tRPC](https://img.shields.io/badge/tRPC-TypeSafe-lightblue)](https://trpc.io/)

**Clique** is a platform for photographers to **sell their photos**, **search for ideas**, and **generate AI images** from prompts. It features a complete admin dashboard, secure payments via Stripe, and MongoDB-powered image storage.

<p align="center">
  <a href="https://www.youtube.com/watch?v=M8Q7_sCL5hY" target="_blank">
    <img src="https://img.shields.io/badge/Watch%20Video-%F0%9F%93%BA-red?logo=youtube&style=for-the-badge" alt="Watch Video on YouTube to know about project" />
  </a>
</p>



## Features

- 🖼️ **Sell Images**: Photographers can upload and monetize their work.
- 🔍 **Search for Ideas**: Get inspired with image results from the **Pexels API**.
- 🤖 **AI Image Generation**: Create custom AI images using natural language prompts.
- 🛠️ **Admin Dashboard**: Built with `tRPC` for managing platform content and users.
- 💳 **Stripe Payments**: Fully integrated payment gateway.
- 🗃️ **MongoDB Storage**: Efficient and scalable image and user data handling.


## Admin Dashboard

Made using tRPC, Admins can:

- Monitor and moderate uploaded images  
- Manage photographers and users  
- Review AI-generated content  
- Handle payments and payouts via Stripe  
- View platform analytics and usage statistics  
## Screenshots

### 🔍 Home Page  
<p align="center">
  <img src="home.png" alt="Home Page" width="100%" />
</p>

### 📤 Upload Page  
<p align="center">
  <img src="upload.png" alt="Upload Page" width="100%" />
</p>

### 💳 Checkout  
<p align="center">
  <img src="checkout.png" alt="Checkout Page" width="100%" />
</p>

### 📊 Admin Dashboard  
<p align="center">
  <img src="admin.png" alt="Admin Page" width="100%" />
</p>

## Tech Stack

| Technology   | Purpose                               |
|--------------|----------------------------------------|
| **Node.js**  | Backend server and business logic      |
| **tRPC**     | Type-safe API communication            |
| **MongoDB**  | NoSQL database for storing image data  |
| **Stripe API** | Payment handling and checkout flow  |
| **Pexels API** | Photo search functionality          |
| **AI Model** | Prompt-based image generation (Stable Diffusion) |


## Installation

```bash
git clone https://github.com/BhaumikReddy/clique_project.git
cd clique
npm install
```
## Deployment

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### Prerequisites

- Node.js v16+
- MongoDB
- Stripe API keys
- Pexels API key

Made with ❤️ by [@BhaumikReddy](https://github.com/BhaumikReddy)

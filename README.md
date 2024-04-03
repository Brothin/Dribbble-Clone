# [Bribbble](https://dribbble-clone-black.vercel.app/)

This project is a Dribbble-inspired platform that allows developers to showcase their projects and connect with the developer community. Bribbble is an app that brings the vibrant and inspiring world of design right to your fingertips. Bribbble is your go-to platform for sharing, discovering, and celebrating creative brilliance, just like the original Dribbble. It offers a dynamic and visually captivating experience for developers. Users can sign in with their email, upload project details, including images, titles, and descriptions, explore other developers' profiles, and easily sort through projects by category. With secure authentication and responsive design, this application encapsulates the core elements of a modern developer portfolio and collaboration platform.

## 🤖 Dribbble Clone

- Search & filter functions
- Authentication using Clerk
- MongoDB & Prisma for database
- Edgestore for image upload
- Zustand for state management
- Hosted in Vercel

## ⚙️ Tech/framework used

- Next.js 14
- Shadcn/ui
- Clerk
- Tailwind CSS
- TypeScript
- MongoDB
- Prisma
- Edgestore
- Zustand
- Vercel

## 🔋 Features

👉 Modern Design Home Page: Features a clean and modern design resembling Dribbble, with a visually appealing interface showcasing project previews and navigation.

👉 Browsing and Pagination: Browse different projects, filter them by category, and experience smooth pagination for seamless data exploration.

👉 Authentication & Authorization System: A fully functional authentication and authorization system allows users to log in securely using JWT and Google authentication.

👉 Create Post Page: Provides a dedicated space for users to share their projects with the community. It includes fields for project details, images, and other relevant information.

👉 Project Details and Related Projects: A detailed view with related projects functionality, enabling users to explore more projects within the same category or theme.

👉 Edit and Re-upload Images: Users have the capability to edit previously created projects, including the ability to re-upload images from their devices to the cloud for updates.

👉 Delete Projects: The delete functionality simplifies project removal with a one-click process, streamlining the user experience.

👉 Portfolio-Style User Profile Page: The user profile page adopts a portfolio-style layout, displaying the user's projects along with the project profiles of other users for easy exploration.

👉 Backend API Routes: Backend API routes for handling JWT token management for secure authentication and image uploading, supporting seamless integration with the frontend.

and many more, including code architecture and reusability

## 🤸 Starting the project

Open the [.env.example](/.env.example) and fill in your Database URL, Edgestore configurations & Clerk Auth Configurations then save it as .env and then run the following commands:

```bash
npm install
npx prisma generate
npx prisma db push
npm run dev
```

## 🚀 Demo

The app is hosted on Vercel. [Click here](https://dribbble-clone-black.vercel.app/) to visit.

## 📸 Screenshots

### Homepage

![Homepage](/screenshots/screenshot-1.png)

### Work

![Work](/screenshots/screenshot-2.png)

### Sign in

![Sign in](/screenshots/screenshot-3.png)

### Sign up

![Sign up](/screenshots/screenshot-4.png)

### E-mail verification

![Verification](/screenshots/screenshot-9.png)
![Email](/screenshots/screenshot-8.png)

### Search

![Search](/screenshots/screenshot-5.png)

### Profile

![Profile](/screenshots/screenshot-6.png)

### Account

![Account](/screenshots/screenshot-10.png)

### Upload

![Upload](/screenshots/screenshot-7.png)

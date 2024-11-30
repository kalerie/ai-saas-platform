<h1 align="center">ImageForge: AI SaaS platform with powerful image processing features</h1>

<div align="center">
  An advanced AI SaaS platform specializing in image processing capabilities. It offers a seamless and secure experience for transforming images with cutting-edge AI features. Users can restore, recolor, enhance, or manipulate images while managing transformations and credits through an intuitive interface.
  See it in action —  <a href="https://ai-saas-platform-orpin.vercel.app/" target="_blank"><b>have a look here!</b></a>

  **PS: To try out the app's features, users simply log in with their email, Github, or Google account for secure access.**
</div>
<br />

## 📋 <a name="table">Table of Contents</a>

- 📌 [Missions/Challenges](#challenge)
- ⚙️ [Tech Stack](#tech-stack)
- 🌟 [Process](#process)
- 🎯 [Result](#result)
- 🤸 [Quick Start (locally set up)](#quick-start)


## <a name="challenge">📌 Missions/Challenges</a>

👇 **Mission:**
   
   The mission was to develop a user-friendly platform that empowers users to manipulate and enhance images effortlessly using AI. Key challenges included:

   - Designing a scalable infrastructure for AI features like object removal, generative fill, and background extraction.
   - Ensuring secure user authentication and seamless credit-based payments.
   - Implementing advanced search capabilities for content and efficient image storage for quick and accurate access.
   - Crafting a responsive and visually appealing user interface adaptable to any device.


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- MongoDB
- Clerk
- Cloudinary
- Stripe
- ShadCN
- Tailwind CSS


## <a name="process">🌟 Process</a>

 1. ✔️ **Frontend Development**

     - **Next.js & TypeScript**: Enabled server-side rendering, API routes, and type-safe coding for efficient development.
     - **ShadCN & Tailwind CSS**: Designed a modern, responsive, and accessible UI/UX, ensuring a seamless user experience across devices.

   2. ✔️ **User Authentication & Authorization**

      - **Clerk**: Integrated a secure authentication system with route protection, user profiles, and metadata management.

   3. ✔️ **Image Processing Features**

       - **Cloudinary**: Utilized for secure image storage, transformations, and delivering optimized image assets.

   4. ✔️ **Payment Integration**

       - **Stripe**: Implemented a secure payment gateway to support the credit system for AI transformations.

   5. ✔️ **Database & Scalability**

       - **MongoDB**: Designed a scalable and efficient schema to store image transformation data, user information, and transaction history.

   6. ✔️ **Backend & API Management**

       - **Next.js API Routes**: Developed secure and optimized server-side endpoints for AI processing, credit updates, and data retrieval.


## <a name="result">🎯 Result</a>

   👉 **Secure & Scalable Platform**: Next.js and MongoDB ensure a fast, reliable, and scalable solution for seamless user experiences.
   
   👉 **Feature-Rich AI Tools**: Cloudinary powers advanced image transformation capabilities like object removal, generative fill, and recoloring.
   
   👉 **Authentication & User Management**: Clerk simplifies user authentication and profile management while integrating securely with the app.
   
   👉 **Effortless Payments**: Stripe provides a secure and straightforward credit purchase system for uninterrupted use of transformations.
   
   👉 **Intuitive UI/UX**: ShadCN and Tailwind CSS deliver a clean, responsive, and modern design that works flawlessly on any device.
   
   👉 **Optimized Image Delivery**: Cloudinary ensures fast and efficient delivery of transformed images, enhancing user satisfaction.


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/kalerie/ai-saas-platform.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

#Clerk urls
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#Clerk webhook secret
WEBHOOK_SECRET=

#MongoDB
MONGODB_URL=

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

#STRIPE webhook secret
STRIPE_WEBHOOK_SECRET=

#Other
NEXT_PUBLIC_SERVER_URL=http://localhost:3000
```

Replace the placeholder values with your actual Clerk, MongoDB, Cloudinary & Stripe credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com) and [Stripe](https://stripe.com/) website.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

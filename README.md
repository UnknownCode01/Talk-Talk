# Talk-Talk

A modern Next.js application for blogging video content, seamlessly integrated with ImageKit. **Talk-Talk** offers a comprehensive platform featuring user authentication, video upload capabilities, and video enjoying experience.

## 🚀 Features
- 🔐 **User Authentication** (NextAuth.js)
- 📹 **Video Upload and Management** (ImageKit)
- 🎨 **Modern UI** with Tailwind CSS and DaisyUI
- 📱 **Fully Responsive Design**
- 🔒 **Secure API Routes**
- 🗄️ **MongoDB Database Integration**

## 🛠️ Tech Stack
- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS, DaisyUI
- **Authentication**: NextAuth.js, JWT
- **Database**: MongoDB with Mongoose
- **File Storage**: ImageKit
- **Form Handling**: React Hook Form

## 📋 Prerequisites
- Latest LTS version of Node.js
- MongoDB Database
- ImageKit Account

## ⚙️ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/UnknownCode01/Talk-Talk.git
   cd Talk-Talk
   ```

2. **Install dependencies:**
   ```bash
   npm i
   ```

3. **Configure environment variables:**
   - Copy the example file:
     ```bash
     cp .env.example .env
     ```
   - Fill in the required environment variables.

4. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔑 Environment Variables
Create a `.env` file with the following configuration:

```env
# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=

# ImageKit
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=

```

## 📜 Available Scripts
- `npm run dev` - Start the development server
- `npm run build` - Build the production application
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint checks
- `npm run seed` - Seed the database

## 📂 Project Structure
```
├── app/                  # Next.js app directory
│   ├── api/              # API routes
│   ├── components/       # Reusable components
│   ├── login/            # Login page
│   ├── register/         # Registration page
│   └── upload/           # Video upload page
├── lib/                  # Utility functions
├── models/               # MongoDB models
├── public/               # Static assets
└── types.d.ts            # TypeScript declarations
```

## 🙅 Contributing
All contributions to take the app towards perfection are accepted.

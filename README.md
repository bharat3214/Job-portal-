# 🧑‍💼 Full Stack Job Portal

A feature-rich Job Portal built with modern web technologies to connect job seekers with employers. It supports job search, applications, job posting, and admin management — all with a clean UI and secure authentication.

---

## 🚀 Features

### 👤 Job Seeker

* Sign up & log in securely via Clerk
* Create and update profile
* Browse and filter jobs by role, location, and experience
* Apply for jobs directly
* View and track application status

### 🏢 Employer

* Create and manage job listings
* View applications submitted by job seekers
* Update job status (open, closed, or filled)


---

## 🧰 Tech Stack

| Layer          | Technology                               |
| -------------- | ---------------------------------------- |
| **Frontend**   | React JS, Tailwind CSS, Shadcn UI        |
| **Backend**    | Supabase (Database + API + Auth)         |
| **Auth**       | Clerk (Authentication & User Management) |
| **Styling**    | Tailwind CSS, Shadcn UI                  |
| **Deployment** | Vercel (recommended)                     |

---

## 📦 Installation

To run this project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/bharat3214/Job-portal-.git
```

### 2. Navigate into the Project Directory

```bash
cd Job-portal
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Add Environment Variables

Create a `.env.local` file and include your Supabase and Clerk credentials:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

### 5. Start the Development Server

```bash
npm run dev
```

### 6. Open in Browser

Visit `http://localhost:3000` to access the portal.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new feature branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push to your fork
5. Submit a pull request

Please follow the project’s code style and best practices.

---





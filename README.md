# ⚡ Next.js + Supabase Starter

A minimal and powerful starter template combining **Next.js** and **Supabase** – perfect for building modern full-stack applications with authentication, database, and storage out of the box.

![Screenshot](./public/preview.png) <!-- Optional: Replace or remove if not available -->

## 🚀 Features

- 🔐 Supabase Auth (Email/Password, Social logins)
- 🗃️ Supabase Database & API integration
- 📦 Fully typed with TypeScript
- 🌗 Dark mode support (optional)
- 💨 Tailwind CSS for rapid UI styling
- 🧪 Ready for testing and deployment

## 🛠 Tech Stack

- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [React](https://reactjs.org/)

## 📦 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/pnvdev/nextjs-supabase-starter.git
cd nextjs-supabase-starter
```

### 2. Install dependencies

```bash
npm install
# or
yarn
```

### 3. Setup Supabase

1. Create a new project at [supabase.com](https://supabase.com)
2. Grab your **Project URL** and **anon/public API key**
3. Create a `.env.local` file:

```bash
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
```

> ✅ You can also configure `SUPABASE_SERVICE_ROLE_KEY` if needed for admin actions (be careful with exposure).

### 4. Run locally

```bash
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` to see the app in action.

## 🌍 Deployment

This starter works great on platforms like [Vercel](https://vercel.com/) or [Netlify](https://netlify.com/).

> Make sure to add the environment variables in the dashboard when deploying.

## 🗂️ Project Structure

```
.
├── components/      # Reusable UI elements
├── lib/             # Supabase client setup
├── pages/           # Next.js routes
├── styles/          # Tailwind/global styles
├── types/           # TypeScript types
├── .env.local       # Local env variables
```

## 📌 TODO / Ideas

- [ ] Supabase Row-Level Security (RLS) examples
- [ ] User profile dashboard
- [ ] SSR/ISR support
- [ ] Dark mode switcher
- [ ] Example with storage uploads

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests.

## 📄 License

[MIT](LICENSE)

---

Built with ❤️ by [pnvdev](https://github.com/pnvdev)

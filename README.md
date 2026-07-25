# UIU CSE Question Bank

A single-page web app where UIU CSE students can search, browse, and download past exam questions, solutions, and notes — organized by semester and course.

**Live:** *[UIU CSE Question Bank](https://question-bank-orpin-psi.vercel.app/)*
**Backend:** [`question-bank-x5pu.onrender.com`](https://question-bank-x5pu.onrender.com)

## Features

- 🔍 **Search & browse** — find materials instantly by course code (e.g. `CSE2215`) or title, with a dashboard, dedicated course list, and semester-wise browsing
- 📚 **Course library** — full UIU CSE curriculum with filters by semester/type
- ⬆️ **Upload flow** — a guided, multi-step uploader for question papers, solutions, and notes, with topic tagging
- ❤️ **Favorites** — save frequently-used courses for quick access
- 🌗 **Light/dark theme** — theme toggle with persisted preference
- 📱 **Mobile-first** — bottom navigation bar and responsive layout tuned for phones
- 📄 **In-browser PDF preview** for uploaded materials

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS — single-file architecture (`index.html`)
- **Auth & Database:** Firebase (Firestore)
- **File storage:** Cloudinary (signed uploads via backend)
- **Backend API:** Node.js service hosted on Render, used for Cloudinary signing and presence/heartbeat tracking

## Getting Started

This is a static single-file app — no build step required.

```bash
git clone https://github.com/Hameme21/UIU_Question_Bank.git
cd UIU_Question_Bank
# open index.html directly, or serve it locally
npx serve .
```

> Note: uploads and live data require the Firebase project and the companion backend to be configured and reachable.

## Related Projects

- [QB_Admin](https://github.com/Hameme21/QB_Admin) — the admin portal used to review, approve, and manage submissions to this question bank

## Contributing

Found a bug or want to add missing course materials? Open an issue or submit a pull request.

## License

Licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

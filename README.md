# 🚀 Resume Wizardry

**Resume Wizardry** is a modern, web-based **resume builder** built with **React + Vite** and styled with **Tailwind CSS**.  
It helps you create clean, **ATS-friendly** resumes, preview them in real time, and export to **PDF, DOCX, or JSON**.  
It also includes an **NLP-powered spell checker** (via [nspell](https://github.com/wooorm/nspell)) to catch typos across the entire resume with one click.

🌐 **Live App:**  
[https://resume-wizardry-kjrv3wjeu-sakina-kayyawalas-projects.vercel.app](https://resume-wizardry-kjrv3wjeu-sakina-kayyawalas-projects.vercel.app)

---

## ✨ Features

- 🖥️ **Real-time preview** — see your resume update instantly while typing.
- 🎨 **Multiple templates** — Clean ATS, Compact One-Page, Elegant Sidebar.
- 📄 **Export options** — PDF, DOCX, and JSON formats.
- 🔍 **Smart spell checker** — checks the entire resume using NLP (Hunspell dictionary via `nspell`).
- 💾 **Auto-save** — your work stays in your browser’s local storage.
- ⚡ **Fully client-side** — no server required, your data stays private.

---

## 🛠️ Tech Stack

- **Frontend:** React 18 + Vite
- **Styling:** Tailwind CSS
- **Icons:** [Lucide Icons](https://lucide.dev/)
- **Spell Checking:** [nspell](https://github.com/wooorm/nspell) + Hunspell dictionaries
- **Export:** `pdfmake` for PDF, `docx` for Word files

---

## 📦 Installation & Local Development

```bash
# Clone the repository
git clone https://github.com/sakinakayyawala18/resume-wizardry.git

cd resume-wizardry

# Install dependencies
npm install

# Start the development server
npm run dev

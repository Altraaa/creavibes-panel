# Creavibes Panel - Project Clone Guide

**Creavibes Panel** adalah aplikasi panel berbasis React + TypeScript + Vite dengan Tailwind CSS untuk styling.

## 📋 Prasyarat

Sebelum memulai clone project ini, pastikan Anda sudah memiliki:

- **Node.js** (versi 18 atau lebih tinggi)
- **npm** atau **yarn** atau **pnpm** (package manager)
- **Git** (untuk clone repository)

## 🚀 Step by Step Clone Project

### 1. Clone Repository

```bash
# Clone repository ini
git clone <https://github.com/Altraaa/creavibes-panel.git>

# Masuk ke direktori project
cd creavibes-panel
```

### 2. Install Dependencies

```bash
# Menggunakan npm
npm install

# Atau menggunakan yarn
yarn install

# Atau menggunakan pnpm
pnpm install
```

### 3. Jalankan Development Server

```bash
# Menggunakan npm
npm run dev

# Atau menggunakan yarn
yarn dev

# Atau menggunakan pnpm
pnpm dev
```

Aplikasi akan berjalan di `http://localhost:5173` (atau port yang tersedia).

### 4. Build untuk Production

```bash
# Menggunakan npm
npm run build

# Atau menggunakan yarn
yarn build

# Atau menggunakan pnpm
pnpm build
```

File build akan berada di direktori `dist/`.

### 5. Preview Build

```bash
# Menggunakan npm
npm run preview

# Atau menggunakan yarn
yarn preview

# Atau menggunakan pnpm
pnpm preview
```

## 🛠️ Teknologi yang Digunakan

- **React** (v19.2.0) - Frontend library
- **TypeScript** (v5.9.3) - Superset JavaScript dengan tipe data
- **Vite** (v7.2.4) - Build tool dan development server
- **Tailwind CSS** (v4.1.17) - CSS framework utility-first
- **ESLint** (v9.39.1) - Linting untuk JavaScript/TypeScript
- **@vitejs/plugin-react-swc** (v4.2.2) - React plugin dengan SWC

## 📁 Struktur Project

```
creavibes-panel/
├── public/                 # File statis
├── src/                   # Source code aplikasi
│   ├── assets/            # Asset gambar/ikon
│   ├── App.tsx            # Komponen utama
│   ├── App.css            # Global styles
│   ├── index.css          # CSS entry point
│   └── main.tsx           # Entry point aplikasi
├── .gitignore             # File yang diabaikan Git
├── eslint.config.js       # Konfigurasi ESLint
├── index.html             # HTML template
├── package.json           # Dependencies dan scripts
├── tsconfig.json          # Konfigurasi TypeScript utama
├── tsconfig.app.json      # Konfigurasi TypeScript untuk aplikasi
├── tsconfig.node.json     # Konfigurasi TypeScript untuk Node.js
└── vite.config.ts         # Konfigurasi Vite
```

## 🔧 Scripts yang Tersedia

- `npm run dev` - Menjalankan development server
- `npm run build` - Build aplikasi untuk production
- `npm run lint` - Menjalankan ESLint
- `npm run preview` - Preview build production

## 📝 Konfigurasi TypeScript

Project menggunakan konfigurasi TypeScript dengan:

- Target: ES2022 (app) dan ES2023 (node)
- Module resolution: bundler mode
- Strict mode: aktif
- JSX: react-jsx

## 🎨 Styling dengan Tailwind CSS

Project menggunakan Tailwind CSS v4 dengan konfigurasi:

- Utility-first CSS framework
- Integrasi dengan Vite melalui `@tailwindcss/vite`
- Auto-import konfigurasi Tailwind

## 🔍 Linting dengan ESLint

ESLint dikonfigurasi untuk:

- TypeScript strict mode
- React hooks rules
- React refresh rules
- Type-aware linting rules

## 🚨 Troubleshooting

### Error: "Cannot find module 'react' atau 'react-dom'"

Pastikan Anda sudah menjalankan `npm install` atau `yarn install`.

### Error: "TypeScript compilation error"

Periksa file `tsconfig.json` dan pastikan konfigurasi sudah sesuai.

### Port sudah digunakan

Development server Vite biasanya menggunakan port 5173. Jika port sudah digunakan, Vite akan secara otomatis menggunakan port yang tersedia.

## 📞 Informasi Tambahan

Untuk informasi lebih lanjut, Anda dapat melihat:

- [React Documentation](https://react.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/)
- [Vite Documentation](https://vite.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/)

---

**Happy Coding! 🎉**

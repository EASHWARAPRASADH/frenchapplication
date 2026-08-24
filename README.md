<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,50:3b82f6,100:ef4444&height=220&section=header&text=FrenchApplication&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Interactive%203D-Powered%20French%20Language%20Learning%20Platform&descFontSize=18&descAlignY=62" width="100%" alt="FrenchApplication Header" />
</div>

<div align="center">

[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![Laravel Framework](https://img.shields.io/badge/Laravel-12.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Three.js](https://img.shields.io/badge/Three.js-3D%20Globe-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-Bundler-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

</div>

---

## 📖 Overview

**FrenchApplication** is a modern, gamified web platform engineered for immersive French language acquisition. Combining the robust backend architecture of **Laravel 12** with an interactive **React + Three.js** frontend, the platform provides learners with dynamic 3D visualizations, interactive vocabulary mini-games, structured curriculum builders, and real-time comprehension tracking.

---

## ✨ Key Features

### 🌐 1. Interactive 3D Word Globe
- Powered by **Three.js** & **React Three Fiber**.
- Features an animated icosahedron wireframe sphere with continuous smooth rotation.
- Visualizes global Francophone linguistic hubs with reactive hover effects.

### 🎮 2. Gamified Vocabulary Mini-Games
- Interactive translation challenges and rapid-fire quiz rounds.
- Real-time score tracking, streak mechanics, and instant feedback loops.
- Level progression from beginner (A1/A2) to intermediate (B1/B2) vocabulary.

### 📚 3. Dynamic Lesson Builder & Curriculum
- Comprehensive module builder allowing structured course organization.
- Categorized vocabulary decks (travel, business, daily conversation, grammar).
- Rich audio-pronunciation guides and contextual sentence examples.

### ⚡ 4. High-Performance Modern Stack
- Blade templating combined with modular React components via Vite.
- Sleek modern design system utilizing **Tailwind CSS**.
- Production-ready deployment configurations (Hostinger, Apache `.htaccess`, Nginx).

---

## 🛠️ Architecture & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | PHP 8.2+, Laravel 12 Framework, Artisan, Eloquent ORM |
| **Frontend** | React 19, TypeScript, Blade Templates, Tailwind CSS, Vite |
| **3D & Graphics** | Three.js, React Three Fiber, Lucide Icons |
| **Database** | MySQL / SQLite with automated schema migrations |
| **Deployment** | Hostinger, Nginx, Apache (`.htaccess`), Vite Static Build |

---

## 🚀 Getting Started

### Prerequisites
- **PHP** >= 8.2 (with OpenSSL, PDO, Mbstring, Tokenizer, XML, Ctype, JSON extensions)
- **Composer** >= 2.0
- **Node.js** >= 18.x & **npm**
- **MySQL** or **PostgreSQL** (or SQLite for local testing)

---

### Local Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EASHWARAPRASADH/FrenchApplication.git
   cd FrenchApplication
   ```

2. **Install PHP and Node dependencies:**
   ```bash
   composer install
   npm install
   ```

3. **Configure Environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Set Database Credentials in `.env`:**
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=french_app
   DB_USERNAME=root
   DB_PASSWORD=
   ```

5. **Run Migrations & Seeders:**
   ```bash
   php artisan migrate
   ```

6. **Start Development Servers:**
   ```bash
   # Terminal 1: Start Laravel backend
   php artisan serve

   # Terminal 2: Start Vite asset compiler
   npm run dev
   ```
   Open **[http://localhost:8000](http://localhost:8000)** in your browser.

---

## 📁 Project Structure

```plaintext
FrenchApplication/
├── app/                  # Controllers, Models, Middleware & Services
├── config/               # Application configuration files
├── database/             # Migrations, seeders, and model factories
├── public/               # Web root (compiled assets, index.php)
├── resources/
│   ├── js/               # React components, Three.js 3D Globe, Mini-Games
│   ├── css/              # Tailwind CSS styles and custom themes
│   └── views/            # Blade template views
├── routes/               # Web and API route definitions
├── docs/                 # Deployment guides and technical architecture specs
└── vite.config.js        # Vite bundler configuration
```

---

## 🌐 Production Deployment

The project includes specialized deployment configurations and guides:
- **Hostinger Shared Hosting:** Follow [`HOSTINGER_DEPLOYMENT_GUIDE.md`](./HOSTINGER_DEPLOYMENT_GUIDE.md)
- **Static Export & Build:** Follow [`STATIC_EXPORT_GUIDE.md`](./STATIC_EXPORT_GUIDE.md)
- **Deployment Checklist:** See [`DEPLOYMENT_CHECKLIST.md`](./DEPLOYMENT_CHECKLIST.md)

---

## 📄 License

This project is open-source software licensed under the [MIT License](LICENSE).

<div align="center">
  <sub>Developed with ❤️ by <a href="https://github.com/EASHWARAPRASADH">Eashwara Prasadh</a></sub>
</div>

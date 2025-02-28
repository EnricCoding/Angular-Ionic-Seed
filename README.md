# 🚀 Angular + Ionic Seed (Latest Versions)

A **highly modular and scalable** **Angular 19 + Ionic 7** seed project, designed for both **web and mobile development**. This template is **PWA-ready**, supports **lazy loading**, and is structured for seamless integration with **Capacitor** to convert into a **mobile app (Android/iOS)**.

---

## 🌟 Features

✅ **Angular 19 + Ionic 7** for web and mobile development.  
✅ **Modular architecture** with clear separation (`core/`, `shared/`, `modules/`, `layouts/`).  
✅ **Lazy Loading** for improved performance.  
✅ **State management** with `NgRx` or `Signals` (optional).  
✅ **JWT Authentication** ready for API integration.  
✅ **Internationalization (`i18n`)** with `ngx-translate`.  
✅ **Fully PWA-ready** using `@angular/pwa`.  
✅ **Capacitor-ready** to transform into a mobile app.  

---

## 📂 Project Structure

```
src/
│   global.scss
│   index.html
│   main.ts
│   polyfills.ts
│   test.ts
│   zone-flags.ts
│
├── app/
│   │   app-routing.module.ts
│   │   app.component.html
│   │   app.component.scss
│   │   app.component.spec.ts
│   │   app.component.ts
│   │   app.module.ts
│   │
│   ├── core/                # Global services, interceptors, and guards
│   │   │   core.module.ts
│   │   ├── guards/          # Route protection and authentication guards
│   │   ├── interceptors/    # HTTP interceptors for API requests
│   │   ├── services/        # Shared services like Auth, API, etc.
│   │
│   ├── models/              # TypeScript interfaces and models
│   │
│   ├── modules/             # Feature-based modules
│   │   ├── auth/            # Authentication module (login, register, etc.)
│   │   ├── home/            # Home module and components
│   │   │   │   home-routing.module.ts
│   │   │   │   home.module.ts
│   │   │   │   home.page.html
│   │   │   │   home.page.scss
│   │   │   │   home.page.spec.ts
│   │   │   │   home.page.ts
│   │
│   ├── shared/              # Shared components, directives, pipes
│   │   │   shared.module.ts
│   │   ├── components/      # Reusable UI components
│   │   ├── directives/      # Custom directives
│   │   ├── pipes/           # Custom pipes
│   │   ├── utils/           # Utility functions
│
├── assets/                  # Static assets (images, icons, etc.)
│   │   shapes.svg
│   ├── icon/
│   │   │   favicon.png
│
├── environments/            # Environment-specific configuration
│   │   environment.prod.ts
│   │   environment.ts
│
└── theme/                   # Styling and theming for the app
    │   variables.scss

```

---

## 📦 Installation

1️⃣ Clone the repository:

```sh
git clone https://github.com/EnricCoding/Angular-Ionic-Seed.git
cd angular-ionic-seed
```

2️⃣ Install dependencies:

```sh
npm install
```

3️⃣ Run the development server:

```sh
ionic serve
```

---

## 📲 Convert to a Mobile App with Capacitor

To enable native app support for **Android/iOS**, run:

```sh
npx cap add android
npx cap add ios
```

---

## 🔗 Technologies Used

- **Angular 19**
- **Ionic 7**
- **ngx-translate (i18n)**
- **Capacitor (for mobile apps)**

---


## 📝 Notes

📌 This **Angular + Ionic Seed** is a **production-ready boilerplate** for projects of any size, supporting **web-first development** with a **smooth transition to mobile apps** when needed. 🚀

🔹 **Contributions & Feedback**  
Feel free to open an issue or submit a pull request if you have suggestions for improvement.

---

### 💻 Author

Developed by **Enric Robert**  

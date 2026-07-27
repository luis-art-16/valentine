# 💝 Valentine's Day Project

![Stitch and Angel](stitch-angel.gif)

Welcome to the repository for my special Valentine's Day project! This project was created with a lot of love (and code) to celebrate this special occasion.

And of course, the goal is for everything to work on the first try so we don't end up looking like this:

![Sad Stitch](stitch-lonely.gif)

---

## 🛠️ Technologies Used

This project uses a fast and modern setup to ensure the best experience:

* **React**
* **TypeScript**
* **Vite** (with HMR and base ESLint rules)

Currently, the template supports two official Vite plugins:
* `@vitejs/plugin-react`: Uses Babel (or oxc in rolldown-vite) for Fast Refresh.
* `@vitejs/plugin-react-swc`: Uses SWC for Fast Refresh.

> **Technical Note:** The *React Compiler* is not enabled in this base template due to its impact on development and build performance. If the application is meant for production, it is recommended to expand the ESLint configuration with type-aware rules (e.g., `eslint-plugin-react-x` and `eslint-plugin-react-dom`).

---

## ⚙️ Setup & Configuration

If you want to use or fork this project, you will need to configure your local environment variables:

* Create or edit the `.env.local` file in the root directory of the project.
* Add your Vercel token to this file to ensure deployment and related services authenticate correctly. 

---

## 🚀 Vercel Deployment Notes

If you are deploying this surprise on Vercel, keep these security rules regarding local configuration files in mind:

* [cite_start]The `.vercel` folder is created when you link a directory to a Vercel project[cite: 14].
* [cite_start]Inside this folder, the `project.json` file contains your Vercel project ID (`projectId`) and the ID of the user or team that owns it (`orgId`)[cite: 15].
* [cite_start]**Security Warning:** No, you should not share the `.vercel` folder with anyone[cite: 16].
* [cite_start]Upon creation, it will be automatically added to your `.gitignore` file to prevent accidental commits[cite: 17].

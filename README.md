# Vue 3 Job Board CRUD App 🧑‍💻 
## 🛠 Technologies Used
<p>
  <a href="https://vuejs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Vue.js-35495e?style=for-the-badge&logo=vue.js&logoColor=4FC08D" alt="Vue.js" />
  </a>
  <a href="https://tailwindcss.com/" target="_blank">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </a>
  <a href="https://axios-http.com/" target="_blank">
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios" />
  </a>
  <a href="https://github.com/typicode/json-server" target="_blank">
    <img src="https://img.shields.io/badge/JSON_Server-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON Server" />
  </a>
  <a href="https://primefaces.org/primeicons/" target="_blank">
    <img src="https://img.shields.io/badge/PrimeIcons-007ad9?style=for-the-badge&logo=primeicons&logoColor=white" alt="PrimeIcons" />
  </a>
  <a href="https://router.vuejs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Vue_Router-35495e?style=for-the-badge&logo=vue.js&logoColor=41B883" alt="Vue Router" />
  </a>
  <a href="https://github.com/SaronY/Tailwind-Vue-Toastification" target="_blank">
    <img src="https://img.shields.io/badge/Vue_Toastification-5a67d8?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue Toastification" />
  </a>
  <a href="https://github.com/greyby/vue-spinner" target="_blank">
    <img src="https://img.shields.io/badge/Vue_Spinner-4fc08d?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue Spinner" />
  </a>
</p>

This project is a simple job board built with **Vue 3** using the **Composition API** and **Vue Router**, styled with **Tailwind CSS**, and enhanced with **Vue Toastification**, **Vue Spinner**, and **PrimeIcons**.

It is a fully functional CRUD application that includes:
- Viewing job listings
- Viewing a single job
- Adding a new job
- Editing an existing job
- Deleting a job

Through building this project, I learned and practiced many Vue 3 fundamentals.

## 🚀 Features & What I Learned

### ✅ Vue 3 Fundamentals
- **Component-Based Architecture**
- **Directives**: `v-if`, `v-else`, `v-for`, `v-bind`, `v-on`
- **Event Handling**: `@click`, `@submit`
- **Forms and v-model Binding**
- **Props and Component Communication**
- **Lifecycle Hooks**: `onMounted`
- **Reactivity with `ref()` and `reactive()`**
- **Computed Properties**
- **Using the Composition API (long and short form)**

### 🛠 CRUD Functionality
- **GET**: Fetch all jobs and a single job
- **POST**: Add new job
- **PUT**: Edit a job
- **DELETE**: Remove a job

### 🧰 Tools & Libraries
- `vue-router` for client-side routing
- `axios` for HTTP requests
- `json-server` to simulate a REST API
- `vue-toastification` for user-friendly notifications
- `vue-spinner` for loading indicators
- `primeicons` for job icons
- `tailwindcss` for modern, responsive styling

---

## 📦 Dependencies
```json
"dependencies": {
  "axios": "^1.9.0",
  "json-server": "^1.0.0-beta.3",
  "primeicons": "^7.0.0",
  "vue": "^3.5.13",
  "vue-router": "^4.5.1",
  "vue-spinner": "^1.0.4",
  "vue-toastification": "^2.0.0-rc.5"
}



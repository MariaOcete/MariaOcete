
# [Maria Ocete](https://mariaocete.com/)

name: Generate GitHub Summary Cards
on:
  schedule:
    - cron: "0 2 * * *"   # se actualiza cada día a las 02:00 UTC
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: MariaOcete
          THEME: 2077   # prueba también 'tokyonight', 'dracula', 'github_dark', etc.

## 📈 Estadísticas de GitHub

![Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=MariaOcete&theme=2077)
![Most Used Languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=MariaOcete&theme=2077)


### 📊 GitHub Stats
![GitHub stats](https://github-readme-stats.vercel.app/api?username=MariaOcete&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight)

### 🧠 Most Used Languages

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MariaOcete&layout=compact&theme=tokyonight&langs_count=6)



Full-Stack Web Developer  

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" title="React" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" alt="Django" title="Django" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/angularjs/angularjs-original.svg" alt="Angular" title="Angular" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/symfony/symfony-original.svg" alt="Symfony" title="Symfony" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" alt="PHP" title="PHP" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" alt="Spring" title="Spring" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" title="Docker" height="28" />
</p>


---

## About Me
I am a web developer with experience building secure and scalable applications, both in frontend and backend. I am particularly interested in **security, testing, and best practices**, and I enjoy creating clear and well-documented projects.  
I easily adapt to remote and collaborative environments and I am continuously improving my technical skills.  

---

## Featured Projects

- **[Personal Portfolio](https://github.com/MariaOcete/Portfolio-readme)**  
  Bilingual website developed with React and Tailwind, deployed on Vercel with a custom domain. Includes a Django backend for handling contact forms with reCAPTCHA and IP restriction.  

- **[Clinic Management App](https://github.com/MariaOcete/clinics-app)**  (In progress)  
  Multi-role platform (admin, clinician, patient) for managing appointments, billing, and medical records. Built with React, Django REST, and PostgreSQL. Features JWT authentication and encrypted file uploads.  

- **[English Learning App](https://github.com/MariaOcete/english_web-readme/blob/main/README.md)**  
  Educational platform with teacher/student roles, placement test, and assignment management. Developed with Java, Spring Boot, and MySQL.  

- **[Tasklist](https://github.com/MariaOcete/TaskList)**  
  My first project with **Angular**, built during my training.  
  Task management application with CRUD functionalities (create, read, update, delete).  
  I also explored using **Symfony/PHP** for the backend and deployment with **Docker Compose**.  

- **Invoice App (CodeArts Solutions)**  
  Development of a complete invoicing and client management system with **Angular (frontend)** and **Symfony/PHP (backend)**, using **PostgreSQL** and deployed with **Docker**.  
  My main contribution was the implementation of the **Admin Dashboard**, which included monthly and quarterly metrics for revenue, invoices, and manager statistics.  
  I also developed the **secure authentication system with Access and Refresh Tokens (HttpOnly cookies)**, improving both security and user experience.  
  *(not public due to confidentiality)*  

---

## Technologies

- **Frontend:** React, Angular, Tailwind, HTML5, CSS3, JavaScript (ES6+)  
- **Backend:** Django REST, Spring Boot/Java, Symfony/PHP, Django/Python  
- **Databases:** PostgreSQL, MySQL  
- **DevOps & Deployment:** Docker, Vercel, Render, GitHub Actions  
- **Security:** JWT (HttpOnly refresh), reCAPTCHA, CORS, IP restriction  
- **Tools:** Git/GitHub, Postman, VS Code, Eclipse, Agile methodologies  

---

## Contact
- Portfolio: [mariaocete.com](https://mariaocete.com/)
- Email: mariaocete93@gmail.com  
- LinkedIn: [linkedin.com/in/maria-ocete-martin](https://www.linkedin.com/in/maria-ocete-martin/)  



# SkillCode
A full-stack web application inspired by LeetCode

A full-stack web application inspired by LeetCode, designed to allow users to create, edit, delete, and test programming questions. This system is built using modern technologies and adheres to a microservices architecture, seamlessly integrating backend and frontend services.

---

**Features**  
- **Question Management**: Full CRUD (Create, Read, Update, Delete) functionality for managing coding challenges.  
- **Answer Testing**: Submit solutions in the form of functions to evaluate their correctness, supporting multiple programming languages.  
- **User-Friendly Dashboard**: Built using Nuxt.js with the Nuxt UI library for a responsive and modern user experience.  
- **Backend API**: Robust and scalable API server written in Go using the Gin framework.  
- **Dockerized Deployment**: A single `docker-compose` command to run the entire application locally.  
- **CI/CD Integration**: Automated pipelines using GitHub Actions to build and push Docker images.  

---

**Technologies Used**  
- **Backend**: Go (Gin framework)  
- **Frontend**: Nuxt.js (Nuxt UI library)  
- **Database**: MySQL (deployed using Docker)  
- **DevOps**: Docker, Kubernetes (K8s)  
- **CI/CD**: GitHub Actions for automated builds and deployment  

---

**Repository Links**  
- [Frontend Repository](https://github.com/TehilaTheStudent/SkillCode-frontend)  
- [Backend Repository](https://github.com/TehilaTheStudent/SkillCode-backend)  

---

**How to Run Locally**  

1. Clone this repository:  
   `git clone https://github.com/yourusername/project-overview.git`  
   `cd project-overview`  

2. Start the system:  
   Run the following command to bring up both the backend and frontend services along with the database:  
   ```bash
   docker-compose up
   ```

3. Access the application:  
   - Frontend: `http://localhost:3000`  
   - Backend API: `http://localhost:8080`  


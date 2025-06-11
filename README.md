# 👋 Hi, I'm Chenyu Wang (王宸禹)

🎓 Graduate Student MCS @ Rice University  
💻 Passionate about Full-Stack Development, AI, and System Design  
📍 Currently based in Houston, TX / Open to global opportunities

---

## 🔧 Tech Stack

**Languages**  
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frameworks & Libraries**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vue.js&logoColor=4FC08D)
![Redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Databases & DevOps**  
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Google Cloud Bigtable](https://img.shields.io/badge/Bigtable-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat-square&logo=heroku&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Tools**  
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=flat-square&logo=Jupyter&logoColor=white)
![Overleaf](https://img.shields.io/badge/Overleaf-47A141?style=flat-square&logo=Overleaf&logoColor=white)


---

## 🌟 Featured Projects

### 🔗 [SnapLink](https://github.com/Ireliaww/Comp_539_Project_Group1)
> A scalable, full-stack URL shortener system built for production-grade reliability, incorporating user authentication, analytics, and DevOps automation.

**Tech Stack:**
- 🖥️ **Frontend:** Vue 3 with Pinia for state management and dynamic routing  
- ⚙️ **Backend:** Java Spring Boot (RESTful APIs) with validation, token-based auth, and layered architecture  
- 🗄️ **Database:** Google Bigtable (NoSQL) for high-throughput key-value storage  
- 🚀 **CI/CD:** GitHub Actions for test + build + deploy, deployed via Heroku/Vercel  
- 📈 **Features:** 
  - Custom and auto-generated short links
  - Expiration dates and visit tracking
  - Secure token-based login/register
  - Role-based access control for link management

> _Designed with separation of concerns, high cohesion, and low coupling in mind — SnapLink is more than just a side project, it’s a complete engineering exercise._

### 📘 [RiceBook](https://github.com/Ireliaww/RiceBook)  
> A React-based mini social media app that mimics core Facebook features, supporting post threads, comments, profile management, and friend systems.

**Tech Stack:**
- ⚛️ **Frontend:** React + Redux Toolkit + React Router  
- 🖧 **Backend:** Node.js + Express (with mock APIs and JWT authentication)  
- 📦 **State Management:** Redux slices with immutability and async logic (Thunk)  
- ✅ **Testing:** Jasmine & Jest for component and reducer testing  
- 🧩 **Features:** 
  - Register/login/logout with input validation and error messages  
  - User profile with avatar upload and ZIP-based geolocation  
  - Newsfeed-style post creation, edit, comment, and following  
  - Expand/collapse comment threads with state persistence

> _Focused on component modularity and state-driven UI, RiceBook showcases frontend architecture in a collaborative SPA project.

### 🖼️ [Multimodal Text-Guided Style Transfer](https://github.com/Ireliaww/COMP646-Project)
> A multimodal framework that enables users to input an image and a natural language style description, then outputs a stylized image using CLIP-based style extraction and Stable Diffusion.

**Key Features:**
- 🧠 **NLP + CV Fusion:** Fine-tuned CLIP model on 2,000 WikiArt paintings to understand art-historical styles and vocabulary  
- 🎨 **Text-to-Style Generation:** Converts text prompts into style embeddings, which guide image generation through diffusion  
- ⚡ **Fast Stylization:** Real-time feed-forward model using IP-Adapter for runtime style transfer without retraining  
- 📊 **Results:** Achieved 0.72 average CLIP similarity score, 19% improvement over baselines, with ~25ms inference on GPU  
- 🧪 **Architecture:** Combines VGG19-based AdaIN layers, CLIP-aligned attention maps, and per-style decoders

> _"Post-Impressionist color palette with Expressionist brushwork"_ – this system can understand and generate stylized art accordingly.

---

## 📈 GitHub Stats

![Chenyu's GitHub stats](https://github-readme-stats.vercel.app/api?username=Ireliaww&show_icons=true&theme=default)

---

## 📫 Contact Me

📮 Email: cw206@rice.edu  
📱 WeChat:  NosTalGiaa_y
🔗 LinkedIn: [linkedin.com/in/rice-eric-wang/](https://www.linkedin.com/in/rice-eric-wang/)

---

_Thanks for visiting my GitHub!_ 😄

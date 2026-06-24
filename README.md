# 🌐 LARAta Studios Website 🌐

Personal portfolio website created to showcase game development, software development, and web development projects. The website serves as both a professional portfolio and the public home of the LARAta Studios brand, providing visitors with detailed project breakdowns, design decisions, challenges, and future development plans.


<img width="2551" height="1372" alt="image" src="https://github.com/user-attachments/assets/96ee5959-568f-4d8f-816a-aabddf7e05cd" />
<img width="2542" height="1370" alt="image" src="https://github.com/user-attachments/assets/226f7e49-38a8-4b33-9ed2-70c735cd1a08" />
<img width="2550" height="1372" alt="image" src="https://github.com/user-attachments/assets/0e4177b5-7401-4351-bb3e-67123c391fa9" />
<img width="2547" height="1372" alt="image" src="https://github.com/user-attachments/assets/2d8f5fd2-4b45-421e-9a3f-6ed5cedb77c9" />




---

## ✅ Visit the website ✅

- Website: [Visit](https://laratastudios.com/)

---

## 💫 Features 💫
### v_1.0
- Responsive design for desktop and mobile devices.
- Dedicated project pages with detailed project breakdowns.
- Dynamic project data system using React and reusable components.
- Interactive project galleries supporting screenshots and future media expansion.
- Smooth section navigation throughout the homepage.
- Mobile-friendly navigation menu.
- Custom domain deployment through GitHub Pages.
- Persistent and scalable architecture for adding future projects.
- Contact section with links to professional profiles and portfolio resources.
- Dark/Light mode support.

### v_2.0 - AI Assistant integration

- Interactive AI-powered portfolio assistant available on homepage.
- Answers questions about my projects, skills, education, and experience.
- Responsive chat interface optimized for both desktop and mobile devices.
- Real-time communication between React frontend and Node.js backend.
- Custom knowledge base containing portfolio information.
- Context-aware responses generated using Google’s Gemini AI model.
- Automatic handling of portfolio-related and unrelated questions.
- Deployed as a full-stack application using GitHub Pages and Railway.


  


---

## 🛠️ Built With 🛠️

### Frontend
- React
- Vite
- JavaScript
- HTML
- CSS

### Backend
- Node.js
- Express.js
- CORS

### Other
- Google Gemini API
- @google/genai SDK
- Git

### Deployment
- GitHub Pages (Frontend)
- Railway (Backend)

---

## 💡 Important Design Decisions 💡
Throught this project I had to take multiple important decisions regarding the projects future. Some of them were:

### 🗂️Data-Driven Project System (v1.0)🗂️
Rather than hardcoding each project page, project information is stored in a centralized data structure. This allows new projects to be added by creating a single project entry instead of building entirely new pages.

### 📱Mobile-First Navigation (v1.0)📱
The navigation system was designed to work effectively on smaller screens through a collapsible menu while maintaining a desktop-friendly layout.

### 🔄Reusable Components (v1.0)🔄
Common sections such as galleries, design decisions, challenges, and feature lists were built as reusable components. This reduces duplicate code and ensures consistency across all project pages.

### 🆎Separating Frontend and Backend (v2.0)🆎
The application was designed with a dedicated React frontend and Node.js backend rather than calling Gemini directly from the browser. This keeps API keys secure and allows backend logic to evolve independently from the user interface.

### 🧱Component-Based Chat Architecture (v2.0)🧱
The chatbot was broken into multiple React components:

- ChatBot
  - ChatButton
  - ChatWindow
    - MessageList
    - ChatInput

This separation improved maintainability and allowed each component to focus on a single responsibility.

### 🧠Custom Portfolio Knowledge Base (v2.0)🧠
Instead of allowing the AI model to answer using general internet knowledge, a structured portfolioData.js file was created containing project, skill, and educational information. This ensures responses remain accurate and focused on my portfolio.

---

## 🎓 What I learned 🎓

This project taught me:
- Building and organizing a large React application using reusable components.
- Managing navigation and dynamic routing with React Router.
- Structuring project data for scalability and maintainability.
- Creating responsive layouts that work across desktop and mobile devices.
- Deploying React applications through GitHub Pages.
- Designing user interfaces that balance visual presentation and functionality.
- Improving user experience through navigation flow and content organization.

### v_2.0 (AI Assistant):
- Building REST APIs with Express.js.
- Creating and consuming asynchronous API endpoints.
- Using environment variables to securely manage API keys.
- Integrating third-party AI services into a web application.
- Managing state across multiple React components.
- Deploying full-stack applications using separate frontend and backend hosting providers.
- Debugging deployment, networking, and CORS issues.
- Designing prompts and knowledge contexts for LLM-powered applications.




---

## 🎯 Technical Challenges 🎯

- Dynamic Project Routing: Creating a system where project pages are generated dynamically from shared project data while still supporting unique project content.
- Scroll Management: Managing scroll position between homepage sections and project pages required careful handling to create predictable navigation behavior.
- GitHub Pages Deployment: React Router and GitHub Pages introduced routing challenges that required adjustments to ensure project pages remained accessible after deployment.

### v_2.0 (AI Assistant):
- Secure AI Integration: The Gemini API key could not be exposed to the frontend. To solve this, all AI requests are routed through a Node.js backend that securely communicates with Gemini.
- Deployment Configuration: The application uses GitHub Pages for the frontend and Railway for the backend. Configuring environment variables, deployment settings, and API endpoints across multiple platforms required careful setup and testing.
- Frontend-to-Backend Communication: During development, the frontend and backend ran on different ports and later on different domains after deployment. This introduced challenges involving API routing, environment configuration, and CORS.

---

## 🔮 Future Improvements 🔮

- Add project demonstration videos directly within galleries.
- Add subtle animations and page transitions.
- Expand project categories as additional work is completed.
- Add analytics to better understand visitor interactions.

- Add conversation memory so the assistant can reference previous messages within a chat session.
- Implement vector search and Retrieval-Augmented Generation (RAG) for more scalable portfolio data retrieval.
- Support markdown formatting and richer response layouts.
- Create an admin interface for updating portfolio information without modifying source code.
- Add analytics to track common visitor questions.
- Integrate project screenshots and links directly into AI responses.


---

## ⚙️ Source Code ⚙️

The full source code is private while the project is in active development.
This repository serves as a showcase of the project, including gameplay footage, technical explanations and playable builds.

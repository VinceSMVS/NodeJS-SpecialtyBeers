# NodeJS-SpecialtyBeers

---

### A full-stack web application for beer enthusiasts, built with **Node.js**, **Express**, and **EJS**, supported by **MongoDB (Mongoose)**.

This project offers users functionalities such as **authentication**, **user profiles**, **beer discovery**, a **personalized recommendation quiz**, and a **social feed** for sharing ratings and reviews.

---
# Video of project
[![ScreenShot](https://github.com/user-attachments/assets/513067f0-d6b1-45fd-ae4c-928d0bf4bcf4)](https://vimeo.com/1098445265?share=copy)




## Project Overview & Key Learning Outcomes

This project provided a deep dive into full-stack web development, enabling me to explore essential backend concepts while further refining my existing front-end skills.

### Backend & Data Management (Node.js, Express, MongoDB/Mongoose)

* **Foundational Understanding of Backend Development:** This project introduced me to **Node.js** and **Express** as frameworks for server-side JavaScript programming. I learned how to define routes, work with middleware, and set up a RESTful API.
* **Database Interaction:** I gained extensive experience working with **MongoDB** and the **Mongoose** ORM to store and manage user and beer data. This included setting up models, performing **CRUD** (Create, Read, Update, Delete) operations, and handling data validation. This was crucial for functionalities like creating new users and fetching existing ones from the database.
* **User Authentication:** I implemented a robust authentication system, covering user registration, login, and session management.

### Frontend Rendering & Structure (EJS)

* **Dynamic Content with EJS:** I utilized EJS (Embedded JavaScript) for server-side templating, which allowed me to dynamically send and present data from the backend to the frontend. This significantly strengthened my understanding of the interaction between the frontend and backend.

### Styling & User Experience (CSS)

* **Advanced CSS Proficiency:** This project further honed my **CSS** skills. I was responsible for creating complex layouts and ensuring an intuitive and **responsive user interface** across various devices. The result is a visually appealing and user-friendly application.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js
* MongoDB (ensure it's running locally or use a cloud service like MongoDB Atlas)
* npm (Node Package Manager)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/NodeJS-SpecialtyBeers.git](https://github.com/your-username/NodeJS-SpecialtyBeers.git)
    cd NodeJS-SpecialtyBeers
    ```
2.  **Install NPM packages:**
    ```bash
    npm install
    ```
3.  **Create a `.env` file:**
    In the root directory of the project, create a file named `.env` and add your MongoDB connection string (and any other necessary environment variables):
    ```
    MONGODB_URI=your_mongodb_connection_string
    SESSION_SECRET=a_strong_secret_key
    ```
4.  **Start the server:**
    ```bash
    npm run devStart
    ```
    The application should now be running on `http://localhost:3000` (or whatever port is configured).

---

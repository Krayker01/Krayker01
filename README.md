<h1>I code, build, and invent 👋</h1>

<div class="container">
  <div class="text">
    <p>Hi! My name is Vlad. My code is my creation, and I always look for new ways to make projects better.</p>
    
    <h2>💻 Skills</h2>
    <p><strong>Frontend:</strong> React, EJS, HTML, CSS, JavaScript (ES6)<br>
       <strong>Backend:</strong> Node.js, Express, REST API, Sessions & Cookies<br>
       <strong>Database:</strong> MongoDB<br>
       <strong>Other:</strong> Python
    </p>
    
    <h2>📂 Projects</h2>
    <p>Here is my current project:</p>
    <ul>
      <li><a href="https://github.com/Krayker01/MERN-ToDo">MERN ToDo App</a></li>
      <li>Demo: <a href="https://mern-todo-xl59.onrender.com">https://mern-todo-xl59.onrender.com</a></li>
    </ul>

    <h2>📫 Contact</h2>
    <p>Email: vlad.yrkevich@gmail.com<br>
       LinkedIn: <a href="https://www.linkedin.com/in/vladyslav-yurkevych/">https://www.linkedin.com/in/vladyslav-yurkevych/</a>
    </p>
  </div>

  <div class="image">
    <img src="/assets/pictures/Phineas_Flynn.png" alt="Phineas Flynn" width="180" />
  </div>
</div>

<style>
  .container {
    display: flex;
    gap: 20px;
    align-items: flex-start;
  }

  .text {
    flex: 1;
  }

  .image {
    flex-shrink: 0;
  }

  /* Мобильная версия */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
      align-items: center;
    }

    .image {
      margin-top: 20px;
    }
  }
</style>

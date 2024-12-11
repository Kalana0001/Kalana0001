<style>
  .glass-card {
    backdrop-filter: blur(10px) saturate(180%);
    -webkit-backdrop-filter: blur(10px) saturate(180%);
    background-color: rgba(255, 255, 255, 0.15);
    border-radius: 12px;
    border: 1px solid rgba(255, 255, 255, 0.3);
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin: 10px;
    max-width: 300px;
    text-align: center;
    transition: transform 0.3s ease-in-out;
  }

  .glass-card:hover {
    transform: scale(1.05);
  }

  .glass-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
  }

  .glass-card img {
    width: 80px;
    height: 80px;
    margin-bottom: 10px;
    border-radius: 50%;
    border: 2px solid rgba(255, 255, 255, 0.4);
  }

  .glass-card h4 {
    color: #fff;
    font-size: 1.2rem;
    margin-bottom: 8px;
  }

  .glass-card p {
    color: #d1d1d1;
    font-size: 0.9rem;
  }
</style>

<div class="glass-container">
  <div class="glass-card">
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/HTML.svg" alt="HTML" />
    <h4>HTML</h4>
    <p>Markup language for structuring web content.</p>
  </div>
  <div class="glass-card">
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/CSS.svg" alt="CSS" />
    <h4>CSS</h4>
    <p>Styling language for designing web pages.</p>
  </div>
  <div class="glass-card">
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/JavaScript.svg" alt="JavaScript" />
    <h4>JavaScript</h4>
    <p>Programming language for dynamic web behavior.</p>
  </div>
  <div class="glass-card">
    <img src="https://github.com/Scar1109/skill-icons/blob/main/icons/React-Dark.svg" alt="React" />
    <h4>React</h4>
    <p>Library for building user interfaces.</p>
  </div>
  <div class="glass-card">
    <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/MySQL-Light.svg" alt="MySQL" />
    <h4>MySQL</h4>
    <p>Database management system.</p>
  </div>
</div>

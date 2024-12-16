import React from 'react';

const GitHubProfileReadme = () => {
  return (
    <div className="p-4 max-w-4xl mx-auto">
      <h1 className="text-3xl font-bold mb-4">👋 Hello, I'm Shalom!</h1>
      
      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">🚀 About Me</h2>
        <p className="text-lg">
          A passionate developer dedicated to creating innovative solutions and 
          continuously learning new technologies.
        </p>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">📊 GitHub Statistics</h2>
        <div className="flex flex-wrap gap-4">
          {/* GitHub Stats Badges */}
          <img 
            src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical" 
            alt="GitHub Stats" 
            className="max-w-md"
          />
          <img 
            src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=radical" 
            alt="GitHub Streak" 
            className="max-w-md"
          />
        </div>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">🔧 Technologies & Tools</h2>
        <div className="flex flex-wrap gap-2">
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
          <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
          {/* Add more technology badges */}
        </div>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">📈 Coding Metrics</h2>
        <div className="flex flex-wrap gap-4">
          {/* Wakatime Coding Stats */}
          <img 
            src="https://github-readme-stats.vercel.app/api/wakatime?username=yourusername&theme=radical" 
            alt="Wakatime Stats" 
            className="max-w-md"
          />
          
          {/* Most Used Languages */}
          <img 
            src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical" 
            alt="Top Languages" 
            className="max-w-md"
          />
        </div>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold mb-2">🌐 Visitor Counter</h2>
        <img 
          src="https://profile-counter.glitch.me/yourusername/count.svg" 
          alt="Visitor Count" 
        />
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-2">📫 Connect with Me</h2>
        <div className="flex gap-4">
          <a href="https://linkedin.com/in/yourusername" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
          </a>
          <a href="https://twitter.com/yourusername" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
          </a>
        </div>
      </section>
    </div>
  );
};

export default GitHubProfileReadme;

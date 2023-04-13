<!-- Basculer entre les modes clair et sombre -->
<button onclick="toggleDarkMode()">Activer le mode sombre</button>

### Hi there 👋

# Kevin-Joel Agbeto

I am a software engineer with a passion for creating innovative, high-performance products. I have a strong background in large-scale software development, as well as in managing complex technical projects. 

Here are some ideas to get you started:

- 🔭 I’m currently working on AI application
- 🌱 I’m currently learning AI, prompt engineering and amazing thing
- 👯 I’m looking to collaborate on innovative projects, development of solid and sustainable solution in IT
- 📫 How to reach me: Linkedin or email
- ⚡ Fun fact: Naruto is the best manga in the world

Connect with me:
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=[https://www.linkedin.com/in/kevin-joel-agbeto-174b5a174/])](https://www.linkedin.com/in/kevin-joel-agbeto-174b5a174/)
[![Twitter](https://img.shields.io/badge/-Twitter-blue?style=flat-square&logo=Twitter&logoColor=white&link=[https://twitter.com/K_Joel_Ag])](https://twitter.com/K_Joel_Ag)

Languages and tools: [<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" />]
<!-- Styles pour le mode sombre et le mode clair -->
<style>
  body {
    background-color: #fff;
    color: #222;
  }

  button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
  }

  /* Styles pour le mode sombre */
  body.dark-mode {
    background-color: #222;
    color: #fff;
  }

  body.dark-mode button {
    background-color: #fff;
    color: #222;
  }
</style>

<!-- Script pour activer/désactiver le mode sombre -->
<script>
  function toggleDarkMode() {
    var body = document.querySelector('body');
    body.classList.toggle('dark-mode');
    var button = document.querySelector('button');
    if (button.textContent === 'Activer le mode sombre') {
      button.textContent = 'Activer le mode clair';
    } else {
      button.textContent = 'Activer le mode sombre';
    }
  }
</script>

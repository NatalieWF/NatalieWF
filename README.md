### Hello World! 👋

<!--
**NatalieWF/NatalieWF** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

 <div class="animated-container">
        <img src="your-image.png" alt="Sua Imagem">
    </div>

    <script src="script.js"></script>

    }
}

.animated-container {
    display: inline-block;
    cursor: pointer;
    transition: transform 0.5s ease-in-out;
}

.rotating {
    transform: rotate(360deg);
}

let isRotating = false;

function toggleRotation() {
    const container = document.querySelector('.animated-container');
    isRotating = !isRotating;

    if (isRotating) {
        container.classList.add('rotating');
    } else {
        container.classList.remove('rotating');
    }
}

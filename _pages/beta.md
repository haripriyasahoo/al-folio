<body style="display: flex; height: 100vh; background-color: #f0f0f0; margin: 0; font-family: Arial, sans-serif;">
    <div class="profile-container" style="text-align: left;">
        <div class="name-container" >
            <b class="name" style="font-size: 24px; margin-right: 10px;">  Haripriya Sahoo  </b>
            <button class="play-button" onclick="playAudio()" style="background-color: white; color: black; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">🔊</button>
        </div>
    </div>
    <div class="social-icons" style="margin-top: 20px;">
            <a href="mailto:haripriya.beta@gmail.com" style="text-decoration: none; color: inherit; margin: 0 10px;">
                <i class="fas fa-envelope" style="font-size: 24px; color: #d14836;"></i>
            </a>
            <a href="https://github.com/haripriyaSahoo" style="text-decoration: none; color: inherit; margin: 0 10px;"> 
                <i class="fab fa-github" style="font-size: 24px; color: #333;"></i>
            </a>
            <a href="https://www.researchgate.net/profile/Haripriya-Sahoo-2" style="text-decoration: none; color: inherit; margin: 0 10px;">
                <i class="fab fa-researchgate" style="font-size: 24px; color: #00cc99;"></i>
            </a>
        <a href="https://www.linkedin.com/in/haripriya-sahoo-81b273197" style="text-decoration: none; color: inherit; margin: 0 10px;">
                <i class="fab fa-linkedin" style="font-size: 24px; color: #0077b5;"></i>
            </a>
        </div>
    <audio id="nameAudio" src="beta.mp3"></audio>
    <script>
        function playAudio() {
            var audio = document.getElementById("nameAudio");
            audio.play();
        }
    </script>
    <p>Ph.D. Student</p>
    <p><i> Machine learning models for interfacial flows </i> </p> 


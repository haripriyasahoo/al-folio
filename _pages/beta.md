


<body style="display: flex; justify-content: center; align-items: center; height: 100vh; background-color: #f0f0f0; margin: 0; font-family: Arial, sans-serif;">
    <div class="profile-container" style="text-align: center;">
        <div class="name-container" style="display: flex; align-items: center; justify-content: center;">
            <h1 class="name" style="font-size: 24px; margin-right: 10px;">Haripriya Sahoo</h1>
            <button class="play-button" onclick="playAudio()" style="background-color: white; color: black; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">🔊</button>
        </div>
    </div>
    <audio id="nameAudio" src="beta.mp3"></audio>
    <script>
        function playAudio() {
            var audio = document.getElementById("nameAudio");
            audio.play();
        }
    </script>
    Ph.D. Student

    *Machine learning models for interfacial flows*

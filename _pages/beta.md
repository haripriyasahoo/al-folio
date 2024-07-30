<body style="display: flex; height: 100vh; background-color: #f0f0f0; margin: 0; font-family: Arial, sans-serif;">
    <div class="profile-container" style="text-align: left;">
        <div class="name-container" >
            <b class="name" style="font-size: 24px; margin-right: 10px;">  Haripriya Sahoo  </b>
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
    <p>Ph.D. Student</p>
    <p><i> Machine learning models for interfacial flows </i> </p> 


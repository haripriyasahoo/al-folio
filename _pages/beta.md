<div class="profile-container" style="text-align: left;">
        <div class="name-container" style="display: flex;">
            <b class="name" style="font-size: 24px; margin-right: 10px;">  Haripriya Sahoo </b>
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
    <p>PhD Student</p>
<!--     <p><i> Machine learning models for interfacial flows </i> </p>
 -->

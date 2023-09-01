---
layout: default
title: Raymond Sheng Blog
---
<head>
<style> 
.row {
    display: flex;
  justify-content: space-between;
}
.column {
  display: flex;
  justify-content: center;
}
.wdn-stretch {
    max-width: 100%;
    height: auto;
    display: block;
    border-radius: 10px;
}
#recordButton {
  width:70px;
  height:50px;
  text-align: center;
  background-color: #42f54e;
}
#recordButton:hover {
  background-color: #42f5b3;
}
#playButton {
    width:70px;
  height:50px;
  text-align: center;
    background-color: #f20707;
}
#playButton:hover {
  background-color: #f25107;
}
.center {
  margin: 0;
  position: absolute;
  left: 50%;
  transform: translate(-50%, 100%);
}
.center2 {
  margin: 0;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
}
img.rounded-corners {
  border-radius:30px;
}
.center3 {
    text-align: center;
    justify-content: center;
    align-items: center;
}
.welcome {
  text-align: center;
  font-size: 25px;
}

</style>
</head>

<html>
<br>
<div class="welcome">Welcome to Raymond's Blog.</div>
<div class="row">
    <div class="column">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/03fcccb9-e6ca-4f75-b00c-408ac15ce7d6' width="250" class="wdn-stretch rounded-corners" style="border: 1px solid; border-image-slice: 1;">
    </div>
    <div class="column">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/67084ce8-d145-4d68-83c7-07d15535dde3' class="wdn-stretch rounded-corners">
    </div>
    <div class="column">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/227c1f2d-c74e-4239-b062-7fd054684ccb' width="250" height="490" class="wdn-stretch rounded-corners">
    </div>
<!-- </div>
    <div class="center3">
    <h1>Audio Recorder</h1>
    </div>
    <br>
    <div class="center">
    <button id="recordButton">Record</button>
    <button id="playButton" disabled>Play</button>
    </div>
    <div class="center2">
    <audio id="audioPlayer" controls></audio>
    </div>

  <!-- <script>
      let mediaRecorder;
      let audioChunks = [];

      const recordButton = document.getElementById('recordButton');
      const playButton = document.getElementById('playButton');
      const audioPlayer = document.getElementById('audioPlayer');

      recordButton.addEventListener('click', () => {
          if (mediaRecorder && mediaRecorder.state === 'recording') {
              mediaRecorder.stop();
              recordButton.innerText = 'Record';
              playButton.disabled = false;
          } else {
              navigator.mediaDevices.getUserMedia({ audio: true })
                  .then(stream => {
                      mediaRecorder = new MediaRecorder(stream);

                      mediaRecorder.ondataavailable = event => {
                          if (event.data.size > 0) {
                              audioChunks.push(event.data);
                          }
                      };

                      mediaRecorder.onstop = () => {
                          const audioBlob = new Blob(audioChunks, { type: 'audio/wav' });
                          const audioUrl = URL.createObjectURL(audioBlob);
                          audioPlayer.src = audioUrl;
                      };

                      mediaRecorder.start();
                      recordButton.innerText = 'Stop Recording';
                      playButton.disabled = true;
                  })
                  .catch(error => {
                      console.error('Error accessing microphone:', error);
                  });
          }
      });

      playButton.addEventListener('click', () => {
          if (audioPlayer.src) {
              audioPlayer.play();
          }
      });
  </script> -->
</html>
<!-- 
| Class Name | Teacher    |
|------------|------------|
| CSA        | Mortenson  |
| AP Stats   | Edelstein  |
| APEL       | West       |
| APUSH      | Swanson    |
| AP Bio     | Cheskaty   | -->


# streamlit-webrtc-short-presentation

# Set up
* Kill heavy processes, or reboot the machine
* Set display resolution lower
* Open demo pages in private window
* Open editor
  * Comment out all the code
* Launch demos on local as fallbacks
* Run all the demos once
* Shutdown notifications

# Contents
* Intro
  * Streamlit: https://streamlit.io/
  * streamlit-webrtc: https://github.com/whitphx/streamlit-webrtc
* Demo: https://share.streamlit.io/whitphx/streamlit-webrtc-example/main/app.py
  * Web-based
  * Consuming real-time video stream from local webcam
  * Applying object detection frame by frame
  * Displaying result frames with bounding boxes
  * Hosted on a public cloud
    * Easy to share
  * Interactive
* Live coding
  * Basics of Streamlit
  * Basic usage of streamlit-webrtc
  * streamlit-webrtc with OpenCV filter
* (Optional) drawbacks of `cv2.VideoCapture` and `cv2.imshow`
* Other examples
  * Speech-to-Text: https://share.streamlit.io/whitphx/streamlit-stt-app/main/app_deepspeech.py
    * STT model: https://github.com/mozilla/DeepSpeech
  * Style Transfer: https://share.streamlit.io/whitphx/style-transfer-web-app/main/app.py
    * Forked from https://github.com/malraharsh/style-transfer-web-app
  * Pictogram: https://share.streamlit.io/whitphx/tokyo2020-pictogram-using-mediapipe/streamlit-app
    * Using MediaPipe
    * Original implementation: https://twitter.com/KzhtTkhs/status/1420390042564927489

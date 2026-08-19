# BeatLight.js - Music Flashlight

BeatLight.js is a lightweight web application that turns your smartphone's LED flashlight into a strobe light that blinks in real-time to the rhythm of music played around you.

[Live Demo](https://dicoba-yuks.github.io/beatlight-app/)

## Features

* **Microphone-Driven Beats:** Detects sound frequencies around your phone using Web Audio API.
* **Smart Flashlight Control:** Triggers your device's camera flash to turn on/off according to music beats.
* **Sensitivity Slider:** Adjustable threshold (0 - 255) to fine-tune sound sensitivity for quiet or loud environments.
* **No Installation Required:** Runs directly inside mobile browsers with HTTPS support.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* **Web Audio API:** For analyzing real-time audio frequencies from the microphone.
* **MediaDevices API (`getUserMedia`):** For microphone access and camera torch control.

## How to Use

1. Open the [Live Demo Link](https://dicoba-yuks.github.io/beatlight-app/) on your mobile browser (HTTPS required).
2. Tap **"Start Music Light"**.
3. Allow microphone and camera access when prompted by your browser.
4. Play loud music near your phone and adjust the **Sound Sensitivity** slider to match the beat.

## License

Created for fun and open learning. Feel free to fork and customize!

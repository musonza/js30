## 01 - javascript drum kit
event listeners, css transitions, play audio
![alt text](img/demo.png)

#### How it works

```window.addEventListener('keydown', playSound);```

- When a user presses a key, that fires a keydown event
- we call the `playSound()` function which checks if the key pressed has a corresponding `audio` element
- if we have the audio we play it
- we also apply css transitions to the current key being played

1. SRP: make audio node play sound and add style on pitch node separately.
2. `audio.currentTime`: voice will triggered by default length until set currentTime equals to zero
3. Event **transitionend** will be triggered when css transition finished
4. **delegate** key event listener so that we don't have to bind event listener on every key element

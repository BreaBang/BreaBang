import { render } from 'github-buttons'

// export function render(options: object, callback: (el: HTMLElement) => void): void;
render(options, function (el) {
  document.body.appendChild(el) 
})

// export function render(anchor: HTMLAnchorElement, callback: (el: HTMLElement) => void): void;
render(anchor, function (el) {
  anchor.parentNode.replaceChild(el, anchor)
})

### <center>Hey I'm Breanna Bang</center>

- 🔭 I’m currently working on a 100-hours project (not ready to share details).
- 🌱 I’m currently building confidence in my knowledge of Javascript through projects.
- 📫 How to reach me: Breanna.Bang@gmail.com
- 😄 Pronouns: She/Her/Hers
- ⚡ Fun facts: I'm a huge fan of Disney's Gargoyles (1994). <a href="https://www.breoutside.com" target="_blank">I teach yoga</a>. I love dogs.

  <div class="button-group pill">
        <a href="https://www.breannabang.com/" class="button primary">Website</a>
        <a href="https://www.linkedin.com/in/breanna-bang/" class="button">LinkedIn</a>
        <a href="https://twitter.com/BreannaBang" class="button">Twitter</a>
        <a href="https://angel.co/u/breanna-bang" class="button">Angellist</a>
        <a href="https://breoutside.com/" class="button">Yoga</a>
    </div>

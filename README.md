# Hey I'm Breanna Bang

- 🔭 I’m currently working on a 100-hours project (not ready to share details).
- 🌱 I’m currently building confidence in my knowledge of Javascript through projects.
- 📫 How to reach me: Breanna.Bang@gmail.com
- 😄 Pronouns: She/Her/Hers
- ⚡ Fun facts: I'm a huge fan of Disney's Gargoyles (1994). <a href="https://www.breoutside.com" target="_blank">I teach yoga</a>. I love dogs.

@import "@primer/css/buttons/index.scss";

// Button group
//
// A button group is a series of buttons laid out next to each other, all part
// of one visual button, but separated by rules to be separate.

.BtnGroup {
  display: inline-block;
  vertical-align: middle;

  @include clearfix();

  // Proper spacing for multiple button groups (a la, gollum editor)
  + .BtnGroup,
  + .btn {
    margin-left: $spacer-1;
  }
}

.BtnGroup-item {
  position: relative;
  float: left;
  border-right-width: 0;
  border-radius: 0;

  &:first-child {
    border-top-left-radius: $border-radius;
    border-bottom-left-radius: $border-radius;
  }

  &:last-child {
    border-right-width: $border-width;
    border-top-right-radius: $border-radius;
    border-bottom-right-radius: $border-radius;
  }

  &.selected,
  &[aria-selected='true'],
  &:focus,
  &:active,
  &:hover {
    border-right-width: $border-width;

    + .BtnGroup-item,
    + .BtnGroup-parent .BtnGroup-item {
      border-left-width: 0;
    }
  }
}

.BtnGroup-parent {
  float: left;

  &:first-child .BtnGroup-item {
    border-top-left-radius: $border-radius;
    border-bottom-left-radius: $border-radius;
  }

  &:last-child .BtnGroup-item {
    border-right-width: $border-width;
    border-top-right-radius: $border-radius;
    border-bottom-right-radius: $border-radius;
  }

  .BtnGroup-item {
    border-right-width: 0;
    border-radius: 0;
  }

  &.selected,
  &[aria-selected='true'],
  &:focus,
  &:active,
  &:hover {
    .BtnGroup-item {
      border-right-width: $border-width;
    }

    + .BtnGroup-item,
    + .BtnGroup-parent .BtnGroup-item {
      border-left-width: 0;
    }
  }
}

// ensure that the focus ring sits above the adjacent buttons
.BtnGroup-item,
.BtnGroup-parent {
  &:focus,
  &:active {
    z-index: 1;
  }
}
<div class="BtnGroup d-block mb-2 ml-0">
  <button class="BtnGroup-item btn btn-outline" type="button">Button</button>
  <button class="BtnGroup-item btn btn-outline" type="button" aria-selected="true">Button</button>
  <button class="BtnGroup-item btn btn-outline" type="button">Button</button>
</div>

 <div class="button-group pill">
        <a href="https://www.breannabang.com/" class="btn btn-primary" type="button">Website</a>
        <a href="https://www.linkedin.com/in/breanna-bang/" class="btn btn-primary">LinkedIn</a>
        <a href="https://twitter.com/BreannaBang" class="btn btn-primary">Twitter</a>
        <a href="https://angel.co/u/breanna-bang" class="bbtn btn-primary">Angellist</a>
        <a href="https://breoutside.com/" class="bbtn btn-primary">Yoga</a>
    </div>
 
---

## Projects 
            
            

### Book Recommender API and App

![alt text](https://github.com/BreaBang/BookRecommenderAPI/blob/main/API.gif.gif))

---

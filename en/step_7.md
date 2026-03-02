<h2 class="c-project-heading--task">More challenge: make a style</h2>

--- task ---
Create a computer printout style and invent your own extra style for your mystery letter.
--- /task ---

--- task ---
Create a new class for an old-fashioned computer printout style:

- Use the `VT323` font from [http://jumpto.cc/web-fonts](http://jumpto.cc/web-fonts){:target="_blank"}
- Use the `computer-paper.png` background image

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 41
line_highlights: 41-45
---

.computer {
  color: black;
  background-image: url('computer-paper.png');
  font-family: "VT323", serif;
}

--- /code ---

</div>

Then, add `class="computer"` to one or more words in your message.
--- /task ---

--- task ---
Create another new class with your own style, and apply it to some words.

You can use these background images too:

+ `rough-paper.png`
+ `canvas.png`
--- /task ---

--- task ---
## Test
Click **Run** and check at least one word uses your printout style and at least one word uses your own new style.
--- /task ---
<h2 class="c-project-heading--task">Challenge: edit more classes</h2>

--- task ---

Now look for the other CSS classes that you used to style your mystery letter. 

--- /task ---


Try transforming `magazine1` style changes the text to all uppercase (capital) letters?


--- task ---

In the `magazine2` style, puts an image behind the text?

--- collapse ---
--- 
title: Answer
---
--- code ---
---
language: css
line_numbers: true
line_number_start: 28
line_highlights: 29
---

.newspaper {
  background-color: antiquewhite;
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
}

.magazine1 {
  background-color: teal;
  color: white;
  font-family: Verdana;
  font-weight: 900;
  text-transform: uppercase;
}

.magazine2 {
  background-image: url('pink-pattern.png');
  color: fuchsia;
  font-family: Verdana;
  font-weight: 900;
}


--- /code ---


--- task ---

Change the `background-image` for `magazine2` to `canvas.png`. 

--- code ---
---
language: css
line_numbers: true
line_number_start: 28
line_highlights: 29
---

.magazine2 {
  background-image: url('canvas.png');
  color: fuchsia;
  font-family: Verdana;
  font-weight: 900;
}

--- /code ---

--- /task ---

--- task ---

Click **Run** to see what happens. 

![A message where the second word 'me' has a beige canvas background.](images/canvas.png)

(If you prefer `pink-pattern.png` you can change it back.)

--- /task ---



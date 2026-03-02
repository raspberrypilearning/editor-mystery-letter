<h2 class="c-project-heading--task">STEP TITLE</h2>

--- task ---

BRIEF SUMMARY OF STEP - one line

--- /task ---

## Editing Classes 

--- task ---

Click on the 'style.css' tab. Find the style for the `newspaper` CSS class.

--- code ---
---
language: css
line_numbers: true
line_number_start: 14
---

.newspaper {
  background-color: antiquewhite;
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
}

--- /code ---

Notice that there's a dot before the name of the class in the CSS file but not in the `<span>` tag in your HTML document.

--- /task ---


Now look for the other CSS classes that you used to style your mystery letter. 

--- task ---

Can you find out how the `magazine1` style changes the text to all uppercase (capital) letters?

--- collapse ---
--- 
title: Answer
---
--- code ---
---
language: css
line_numbers: true
line_number_start: 20
line_highlights: 25
---

.magazine1 {
  background-color: teal;
  color: white;
  font-family: Verdana;
  font-weight: 900;
  text-transform: uppercase;
}

--- /code ---

--- /collapse ---

--- /task ---

--- task ---

Can you find out how the `magazine2` style puts an image behind the text?

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

.magazine2 {
  background-image: url('pink-pattern.png');
  color: fuchsia;
  font-family: Verdana;
  font-weight: 900;
}

--- /code ---

--- /collapse ---

--- /task ---

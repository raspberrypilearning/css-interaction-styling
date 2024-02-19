When writing CSS you might want to change the styling on an element when the user interacts with it. 

In the example above, you are changing the styling of the `a` elements, but only when a user **hovers** over them with their mouse. The syntax for this is `a:hover`. 

The style in this selector will **only** be used when a user's mouse is on top of the element.

--- code ---
---
language: css
filename: style.css
---

.nav-items > a:hover {
  color: white;
}

--- /code ---
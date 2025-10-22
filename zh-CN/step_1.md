编写 CSS 时，你可能希望在用户与元素交互时更改元素的样式。

在下面的例子中，`a` 元素的样式发生了改变，但只有当用户用鼠标**悬停**在它们上面时才会改变。 其语法是 `a:hover`。

此选择器中的样式**仅**在用户的鼠标位于元素顶部时使用。

--- code ---
---
language: css
filename: style.css
---

.nav-items > a:hover {
  color: white;
}

--- /code ---

Lorsque tu écris du CSS, tu souhaiterais peut-être modifier le style d'un élément lorsque l'utilisateur interagit avec lui.

Dans l'exemple ci-dessous, le style des éléments `a` est modifié, mais uniquement lorsqu'un utilisateur les **survole** avec sa souris. La syntaxe est `a:hover`.

Le style de ce sélecteur sera **uniquement** utilisé lorsque la souris de l'utilisateur se trouve au-dessus de l'élément.

--- code ---
---
language: css
filename: style.css
---

.nav-items > a:hover {
  color: white;
}

--- /code ---

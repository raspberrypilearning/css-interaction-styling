Wanneer je CSS schrijft, wil je misschien de opmaak van een element wijzigen wanneer de gebruiker ermee communiceert.

In het onderstaande voorbeeld wordt de opmaak van de `a`-elementen gewijzigd, maar alleen wanneer een gebruiker er met de muis overheen **beweegt**. De syntaxis hiervoor is `a:hover`.

De opmaak in deze selector wordt **alleen** gebruikt wanneer de muis van de gebruiker zich boven het element bevindt.

--- code ---
---
language: css
filename: style.css
---

.nav-items > a:hover {
  color: white;
}

--- /code ---

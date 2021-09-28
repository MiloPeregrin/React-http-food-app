# O projektu

Tutoriálový projekt z kurzu [React - The Complete Guide ](https://www.udemy.com/course/react-the-complete-guide-incl-redux/).

Autor: Maximilian Schwarzmüller

---

Vytvořen pomocí **react-create-app**.

K lokálnímu stylování componentů pouužity **CSS Modules**.

Lokální state management pomocí **useState** & **useRef** hooks, cross-component state pak pomocí **useContext** & **useReducer**.

Jako dummy backend použita [Firebase](https://firebase.google.com/), z níž byl pomocí **http request** metodou GET získán seznam uložených pokrmů, data dynamicky vyrenderována v appce a metodou POST zase odeslán seznam objednaných pokrmů zpět do databáze.

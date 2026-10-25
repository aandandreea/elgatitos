# El Gatitos 

A cat adoption website built with plain HTML, CSS and JavaScript.

## Pages

- **Home (`index.html`)**: introduction to the site and a call to adopt a cat.
- **Cats (`cats.html`)**: the list of cats available for adoption, shown as cards in a responsive grid.
- **Adopt (`adopt.html`)**: an adoption request form with built-in browser validation.

## Technologies

- **HTML5**: semantic structure (`header`, `nav`, `main`, `section`, `article`, `footer`) and forms.
- **CSS3**: Flexbox for the header, CSS Grid for the cat cards, hover effects and responsive layout.
- **JavaScript**: cat data stored in an array of objects, cards generated dynamically, and filtering (in progress).

## Project structure

```
El-Gatitos/
├── index.html
├── cats.html
├── adopt.html
├── styles.css
├── script.js
├── images/
└── README.md
```

## Roadmap

- [ ] Filter cats by gender and breed
- [ ] "Adopt" button on each card that marks the cat as adopted
- [ ] Handle the adoption form with JavaScript and show a thank you message
- [ ] Move the cat data to a `cats.json` file and load it with `fetch()`
- [ ] Publish the site with GitHub Pages

## Note

All cat names and descriptions are made up for practice. This is not a real adoption service.

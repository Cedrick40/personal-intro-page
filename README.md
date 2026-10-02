# Personal Introduction Page

A simple single-page personal website built for Task 2 (Personal Introduction Page) of my Web Development internship.

**Live page:** https://cedrick40.github.io/personal-intro-page/

## About the project

The page introduces me, Cedrick Niyibikora. It has my name, a profile image, a short introduction, my skills, my hobbies, and my contact information, organized in the sections About, Skills, Hobbies, and Contact.

## Objective

To practice basic HTML elements, CSS selectors, spacing, colors, and a simple page layout.

## Tools used

- HTML5
- CSS3
- VS Code
- Git and GitHub (free)

## My approach

1. **Planning:** I decided what to include (name, photo, introduction, skills, hobbies, contact) before writing code.
2. **HTML structure:** I used a `head` with the charset, viewport, title, and stylesheet link, then a `header`, a `main` with four `section` elements, and a `footer`. I used headings (`h1`, `h2`) and paragraphs for text, and lists for skills and contact details.
3. **Colors:** I took the palette from my profile photo: plum from my shirt, palm green from the leaves, and cream from the background.
4. **CSS selectors:** I used element selectors (`header h1`), class selectors (`.section`), id selectors (`#skills ul`, `#contact ul`), descendant selectors (`header img`), and pseudo-classes and pseudo-elements (`a:hover`, `li::marker`).
5. **Spacing and typography:** I kept one font stack, the same heading sizes, and the same padding and margin between all sections so the page looks consistent.
6. **Layout:** A centered container with `max-width: 760px`, a flexbox header with a round profile photo, and a two-column skills list. A media query for small screens stacks the header and reduces sizes on phones.
7. **Testing:** I checked the page at desktop size and in the browser's phone view.

## Project structure

```
personal-intro-page/
├── index.html
├── style.css
├── images/
│   └── profile.jpg
└── README.md
```

## Outcome

A clean, simple, and consistent personal introduction page that meets all the task deliverables and works on desktop and mobile. This task taught me how selectors and specificity decide which styles apply, and how consistent spacing and a small color palette make a page look tidy.

## Author

Cedrick Niyibikora
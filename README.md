# Octocats

This is a responsive website cloned after (https://octodex.github.com/)

# Objectives

- Build on your knowledge of HTML & CSS
- Implement, from scratch, a given design
- Understand HTML/CSS Layout
- Be able to place elements on a page where you want them.
- Use flexbox and grid techniques layout pages.
- Work with media queries to build a responsive page.

# Includes

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [FLEXBOX](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [GRID](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)

# Featured Code

## Media Query

```JSX
@media (min-width: 1010px) {
  nav {
    padding: 0;
    margin: 0;
  }

  main {
    display: grid;
    grid-template-columns: repeat(3, 30%);
    grid-column-gap: 2.5rem;
    grid-row-gap: 1rem;
  }

  .logo {
    padding: 1rem 0;
  }

  p {
    font-size: 0.9rem;
  }
}
```

# Live Site

- [LIVE SITE](https://octocats-sam.netlify.app/)

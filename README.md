## Sidebar CSS

- Hidden checkbox toggles sidebar (no JavaScript).
- Sidebar slides in from the left when checked.
- Hamburger icon hides when sidebar opens.
- Close icon fades in when sidebar opens.
- Smooth transitions (0.3s) for sliding and hover.
- Social icons scale up and become clearer on hover.
- Sidebar links show soft box-shadow on hover.
- 

## Key CSS Techniques:

- `position: fixed` sidebar with `left: -300px` off-screen start.
- `~` sibling combinator to target `.sidebar_menu` and icons based on `#check` state.
- `opacity` and `transform` for hover animations.

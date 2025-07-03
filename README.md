## Sidebar CSS

- Uses a hidden checkbox to toggle the sidebar in/out with pure CSS — no JavaScript needed!
- Sidebar slides in from the left when `#check` is checked.
- Hamburger icon disappears when sidebar is open.
- Close icon fades in when sidebar is open.
- Smooth transitions (`transition: all 0.3s linear`) for slide and icon hover effects.
- Social icons get a hover scale and opacity effect.
- Sidebar links highlight with a subtle box-shadow on hover.
- Fully responsive: works on any screen size.

## Key CSS Techniques:

- `position: fixed` sidebar with `left: -300px` off-screen start.
- `~` sibling combinator to target `.sidebar_menu` and icons based on `#check` state.
- `opacity` and `transform` for hover animations.

# Frontend Mentor - Profile card component solution

This is a clean, responsive, and modern solution to the Profile card component challenge on Frontend Mentor.

## Links

- Solution URL: [https://github.com/veon321/Profile-card-component](https://github.com/veon321/Profile-card-component)
- Live Site URL: [https://veon321.github.io/Profile-card-component/](https://veon321.github.io/Profile-card-component/)

## Built with

- **Semantic HTML5 markup** (including `<main>` wrapper, proper header text hierarchy, and isolated metric blocks)
- **CSS Custom Properties (Variables)** for strict adherence to the design system's color scheme and unified font handling
- **Flexbox layout** for multidirectional alignment (card centering, vertical content stacking, and horizontal stat distribution)
- **Modern CSS Math Functions (`clamp()`)** for completely fluid typography, adaptive paddings, and dynamic component sizing
- **Google Fonts** (Kumbh Sans)

## Features

- **Advanced Multi-Asset Background:** Implements a layered `background-image` technique on the body to handle two separate SVGs, placing them dynamically via viewport-relative positioning without interfering with the centered content.
- **Fluid Typography & Adaptive Spacing:** Font sizes and section paddings utilize `clamp()` logic to seamlessly adapt across mobile viewports, high-end tablets, and large desktop screens without rigid breakpoint snap-points.
- **Perfect Inline Stacking Solution:** Fixes the default inline image baseline gaps by overriding the header element with `display: block`, establishing a seamless visual connection between the card header artwork and the main body background.
- **Precise Absolute Positioning:** Uses absolute container translation to offset the profile avatar image exactly 50% across the boundary of the card's upper design asset, precisely matching the professional design specification.
- **Robust Screen Centering:** Utilizes `min-height: 100vh` combined with layout flex alignment to guarantee the component remains centered in the viewport on desktops while remaining fully scrollable on smaller viewports.

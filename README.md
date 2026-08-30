# HTML + CSS Limit Test

An interactive exhibition built to test how far the modern web platform can go without JavaScript, packages, frameworks, image assets, web fonts, build tools, or external requests.

The project is both an argument and its evidence: five semantic HTML documents, one stylesheet, and zero runtime dependencies.

## Explore

- `index.html` — the thesis, performance receipt, and 36-state CSS composition laboratory
- `museum.html` — six inspectable browser-native capability exhibits
- `control-room.html` — live feature detection, Boolean logic, typed variables, meters, and scroll snap
- `engine.html` — a playable CSS machine, exact-state puzzle, 3D inspector, X-ray view, and 144-state poster forge
- `principles.html` — an editorial field guide with a dedicated print edition
- `styles.css` — the complete visual and interaction system

## Demonstrated capabilities

| Capability | Where it appears |
| --- | --- |
| Relational state with `:has()` | Museum parent-state exhibit and shipping checklist |
| Native Popover API | Museum top-layer exhibit |
| CSS anchor positioning | Museum spatial-logic exhibit |
| Container queries and units | Resizable museum specimen and composition typography |
| Scroll-driven animation | Reading progress and exhibit entrances |
| Cross-document view transitions | Navigation across the exhibition and the Control Room-to-Engine core morph |
| Native form validation | Homepage transmission form and museum controls |
| Radio/checkbox state machines | 36-state composition laboratory |
| CSS Boolean logic | Control-room AND, OR, and XOR switchboard |
| Typed custom properties | Animated control-room conic reactor |
| Live CSS feature queries | Control-room capability scan |
| Native meters and scroll snap | Control-room status console and protocol deck |
| Exact-state CSS puzzle | Cascade Engine three-relay vault using `:has()`, `:checked`, and `:not()` |
| CSS 3D transforms | Six-faced inspection model with three stateful viewpoints |
| Scroll-built composition | Cascade Engine components assembled on a named view timeline |
| Document X-ray mode | Live semantic structure labels generated from data attributes |
| Generative design system | 144-state poster forge with a print-to-paper output mode |
| CSS counters | Automatically numbered nested museum system |
| Generated artwork | Every illustration and texture across the site |
| User preference queries | Reduced motion, increased contrast, and print |
| Fluid intrinsic layout | All pages from 320px upward |

## Run locally

No installation is required. Open `index.html` directly, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project constraints

The rendered site must ship:

- no JavaScript
- no packages or dependency manifests
- no image, video, or audio assets
- no external fonts, stylesheets, analytics, or network requests
- no build step

Repository documentation and CI configuration are not runtime assets. The GitHub workflow verifies that the constraint remains intact.

## Accessibility

The documents use landmarks, heading hierarchy, skip links, real links and buttons, a CSS-only mobile menu, labelled fieldsets, keyboard-visible focus, native validation and disclosure, reduced-motion handling, increased-contrast handling, reader-controlled typography, and print-specific reading and poster formats.

Modern capabilities are progressively enhanced. The content and basic controls remain available when an experimental visual feature is unsupported.

## Browser support

The core content and layout work in current evergreen browsers. Individual museum exhibits intentionally demonstrate newer platform features such as anchor positioning, scroll timelines, and cross-document view transitions; unsupported browsers receive stable fallback layouts.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing a change. Any contribution must preserve the zero-JavaScript, zero-dependency runtime.

## License

Released under the [MIT License](LICENSE).

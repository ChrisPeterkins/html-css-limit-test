# Contributing

Contributions are welcome when they strengthen the central experiment: demonstrating browser-native capability with semantic HTML and CSS alone.

## Before opening a pull request

1. Keep all runtime behavior in HTML and CSS.
2. Do not add JavaScript, package manifests, build tools, image assets, external fonts, or third-party requests.
3. Use the most appropriate semantic HTML element before creating a styled substitute.
4. Preserve full keyboard access and visible focus.
5. Add reduced-motion behavior for new animation.
6. Test at 320px, 768px, and a desktop width.
7. Check the print preview when changing the field guide.
8. Explain which native browser capability the change demonstrates.

## Local review

Serve the directory with any static file server:

```sh
python3 -m http.server 8000
```

Inspect all three pages, operate every control using only a keyboard, and verify that the browser console contains no errors.

## Style

- Use two-space indentation in HTML and CSS.
- Prefer logical properties and intrinsic layout.
- Keep selectors readable and group related capabilities.
- Progressive enhancement is preferred to browser-specific workarounds.
- Comments should explain intent or platform behavior, not restate declarations.

## Commit messages

Use concise imperative messages such as `Add anchor positioning exhibit` or `Improve field-guide print layout`.

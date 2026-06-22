# Contributing to Binaris

Thank you for your interest in contributing to Binaris.

## Getting Started

### Fork and Clone

Fork the repository on GitHub, then clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/binaris.git
cd binaris
```

## Development

Binaris is a single HTML file. No build tools, no dependencies, no framework.

```bash
open index.html
```

Edit `index.html` in any code editor. Refresh your browser to see changes.

## Project Structure

```text
binaris/
├── index.html          Main application
├── binaris.png         Logo
├── README.md           Project overview
├── LICENSE             MIT license
├── NOTICE              Legal notices
├── CONTRIBUTING.md     This file
├── CODE_OF_CONDUCT.md  Community guidelines
└── SECURITY.md         Security policy
```

## How to Contribute

### Adding a New JWT Tool

1. Open `index.html`
2. Add a tool definition to the tools array:

```javascript
{ id: 'newtool', name: 'Tool Name', desc: 'Description', icon: '<svg>...</svg>' }
```

3. Create the UI function:

```javascript
function newToolPage() {
    return '<div class="input-wrap">...</div>';
}
```

4. Create the logic function:

```javascript
function newToolLogic() {
    // Your tool logic here
}
```

5. Add routing in the `page()` function
6. Test with real JWT tokens
7. Submit a pull request

## Code Style

- Use single quotes for strings
- Use `var` for variables
- Keep functions small and focused
- Comment complex logic
- Test all 8 tools before submitting

## Bug Fixes

1. Open an issue describing the bug
2. Fork and fix
3. Submit a pull request referencing the issue

## Pull Request Process

1. Ensure all tools still work
2. Update documentation if needed
3. Describe your changes clearly
4. Link any related issues

## Questions

Open an issue or contact the maintainer.

---

Thank you for contributing.
# sass

## Checking if Sass is Installed

To check if Sass is already installed on your Mac, run:

```bash
sass --version
```

## Installation

To install Sass (requires nvm and npm):

```bash
npm install -g sass
```

## Compiling SCSS to CSS

To compile your SCSS file to CSS:

```bash
sass styles/table.scss styles/table.css
```

## Testing Your File

**Option 1: Open Directly in a Browser**
- Simply open `index.html` in your browser (no server needed).

**Option 2: Use a Local Dev Server (Recommended for Development)**
- Install the Live Server extension.
- Right-click on `index.html`.
- Click "Open with Live Server".

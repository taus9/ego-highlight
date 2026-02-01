# ego-highlight

A very basic Ego syntax highlighting extension for VS Code.

https://github.com/taus9/ego

## Clone the repository

```bash
git clone https://github.com/taus9/ego-highlight.git
cd ego-highlight
```

## Build the extension

Make sure you have Node.js and npm installed.

Install dependencies (if needed):

```bash
npm install
```

Package the extension with `vsce` using `npx`:

```bash
npx vsce package
```

This will create a `.vsix` file in the project directory (for example, `ego-highlight-0.1.0.vsix`).

## Install the VSIX in VS Code

You can install the generated `.vsix` file in VS Code in either of these ways:

1. **Using the command line**

   ```bash
   code --install-extension ego-highlight-0.1.0.vsix
   ```

2. **Using the VS Code UI**
   - Open VS Code
   - Go to the Extensions view
   - Click the `...` menu in the top-right corner
   - Choose **Install from VSIX...**
   - Select the generated `.vsix` file

After installation, reload VS Code if prompted.

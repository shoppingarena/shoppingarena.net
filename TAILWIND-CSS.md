# Start with standalone Tailwindcss CLI

**Source:**
[Standalone CLI: Use Tailwind CSS without Node.js](https://tailwindcss.com/blog/standalone-cli)

## Installation for WSL Ubuntu

```bash
# Download the latest version of the CLI
curl -sLO https://github.com/tailwindlabs/tailwindcss/releases/latest/download/tailwindcss-linux-x64

### Make it executable
chmod +x tailwindcss-linux-x64

# Rename to tailwindcss
mv tailwindcss-linux-x64 tailwindcss

# Create a tailwind.config.js file
./tailwindcss init

# Start a watcher
./tailwindcss -i input.css -o output.css --watch

# Compile and minify your CSS for production
./tailwindcss -i input.css -o output.css --minify
```

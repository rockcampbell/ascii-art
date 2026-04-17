# ASCII Art Converter

A browser-based tool that converts any image into ASCII art — no server, no uploads, no dependencies.

**Live at:** [rockcampbell.com/ascii-art](https://rockcampbell.com/ascii-art)

## Features

- Adjustable character size (4–24px)
- Multiple character sets: detailed, simple, block characters, binary, dots
- Colorized output (maps original pixel colors to characters) or monochrome
- Invert brightness option
- Download result as PNG
- Copy raw text to clipboard
- Fully client-side — your image never leaves your browser

## How it works

1. The uploaded image is sampled at a resolution matching the chosen character size
2. Each sample's luminance is mapped to a character from the chosen set (dense chars = dark areas)
3. Characters are rendered onto a canvas — optionally using the original pixel colors
4. The result can be downloaded as PNG or copied as plain text

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no build step.

## License

MIT

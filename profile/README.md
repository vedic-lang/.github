[![Vedic](./images/vedic-banner.svg)](https://vedic-lang.github.io/)

# Programming in Sanskrit

Vedic lets you write programs with Sanskrit keywords and Devanagari numerals. The same Rust interpreter runs on your computer and in the browser.

**[Try Vedic in your browser](https://vedic-lang.github.io/vedic-ide/?example=hello-world.ved)** · [First lesson](https://vedic-lang.github.io/hello-world) · [Language reference](https://vedic-lang.github.io/language-reference)

## Write your first program

`वद` prints a value. Paste this line into the editor and press **Run**. You’ll see `नमस्ते विश्व!` (“Hello, world!”) in the console.

```vedic
वद("नमस्ते विश्व!");
```

To run it locally, save the line as `hello.ved`. Install Vedic with Homebrew, then run the file.

```sh
brew install vedic
vedic hello.ved
```

[More installation options for macOS, Linux, and Windows](https://vedic-lang.github.io/download)

## Build with us

| Project | What you can work on |
| --- | --- |
| [Vedic](https://github.com/vedic-lang/vedic) | The interpreter, command-line tools, and language tests |
| [Online IDE](https://github.com/vedic-lang/vedic-ide) | The browser editor and WebAssembly integration |
| [Documentation](https://github.com/vedic-lang/vedic-lang.github.io) | Lessons, examples, and the language reference |
| [Code Highlighter](https://github.com/vedic-lang/vedic-code-highlighter) · [Code Formatter](https://github.com/vedic-lang/vedic-code-formatter) | Syntax highlighting, formatting, and running programs in VS Code |

Joining the project? The [contributor guide](https://github.com/vedic-lang/vedic/blob/main/CONTRIBUTING.md) explains how to build the interpreter and run its tests.

# Intel Take-home Assignment
It is a small assignment to talk with the intel senior engineer. This achieves two things:
- [Actual Assignment: A personal portfolio based on some of my project](#original-purpose)
- [Reusable presentational markdown designed for Intel + example](#i-want-to-use-it)

# Original Purpose
These are how to generate file/presentation by:
- [vscode](#i-have-vs-code)
- [node](#i-am-a-terminal-person)
- [I am none of these!](#go-get-vs-code)

## I have VS Code
- `$ git clone https://github.com/lukeschoolmode/intel-take-home.git`
- Open VS Code
- Get an extension called "Marp for VS Code"
- In VS Code, open `portfolio.md` (for Korean, `kr-portfolio.md`)
- Open [Palette](https://docs.github.com/en/codespaces/codespaces-reference/using-the-vs-code-command-palette-in-codespaces) and type   `Marp: Export Slide Deck`
- Select the desired format(pdf, pptx, html, png, ... ) and export
- Do presentation to your boss

## I am a terminal person
**NOTE**
- For terminal option, some visual componnents are gone
- Don't ask me. Ask [Marp](https://github.com/marp-team/marp-cli) guys

Requirement: Google Chrome, Chromium, or Microsoft Edge
```
$ git clone https://github.com/lukeschoolmode/intel-take-home.git
$ ls intel-take-home
$ npm install --save-dev @marp-team/marp-cli
(pptx) $ npx @marp-team/marp-cli portfolio.md -o portfolio.pptx
(pdf) $ npx @marp-team/marp-cli portfolio.md -o portfolio.pdf
(html) $ npx @marp-team/marp-cli portfolio.md -o portfolio.html
```

## Go get VS Code

options:
- [vscode](https://code.visualstudio.com)
- [vscodium](https://github.com/VSCodium/vscodium)

[Are you done?](#i-have-vs-code)

# I want to use it

Assume you have VS Code ([You don't?](#go-get-vs-code))
- `$ git clone https://github.com/lukeschoolmode/intel-take-home.git`
- Open VS Code
- Get an extension called, "Marp for VS Code"
- Open `portfolio.md` in VS Code
- On the top right, You should see a button for "Open Preview to the Side". Click that
- Now tinker the code and see what to change/add

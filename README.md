**This extension is still in development. Things may not work correctly. Things may break. The world may end.**

# About

This extension was developed largely in response to the horrible quality of Ada syntax highlighters, whether for VS Code or otherwise. It's all too apparent they were created by people who barely, if at all, work with the language.

# Features

* Highlighting for **pragmas** and **aspects**.
* Highlighting for **types**, something often missed, and as I understand it only also seen in GPS.
* Context aware highlighting, such as `return` being classed differently in function declarations versus control statements, or `exception` being classed as a keyword when introducing exception handler blocks, but as a type when declaring exceptions.
* Highlighting for `.adc` files and basic support for `.gpr` files, not just `.adb` and `.ads`.
* Some snippets for `.gpr` files.

# Proofs in the Screenshot

![screenshot](1.jpg)
![screenshot](2.jpg)

# Help Me Out

Good quality extensions take a lot of time. Considerably more than just "meh, close enough" level work. If you'd like to help out but don't know how to contribute to the code, consider donating to my [Patreon](https://www.patreon.com/Entomy). Leave a message with the donation about it being for this extension, and I'll weight my work towards this.
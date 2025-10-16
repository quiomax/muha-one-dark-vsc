# Muha One Dark Theme

A simplified dark theme based on One Dark Pro with reduced syntax highlighting complexity, following the principles outlined in the article [Don't Highlight Syntax](https://tonsky.me/blog/syntax-highlighting/).

## Features

- Based on One Dark Pro's Darker theme for the main variant
- Includes a GNOME variant for different aesthetic preferences
- Simplified syntax highlighting to reduce visual noise and improve focus
- All UI colors inherited from the base One Dark Pro theme
- Dark theme suitable for extended coding sessions

## Installation

1. Install VSCodium or Visual Studio Code
2. Open the Extensions view (Ctrl+Shift+X)
3. Search for "Muha One Dark"
4. Click Install

Alternatively, you can install from the command line:

```sh
  code --install-extension quiomax.muha-one-dark
```

## Usage

After installation, you can activate the theme by:

1. Opening Command Palette (Ctrl+Shift+P)
2. Typing "Preferences: Color Theme"
3. Selecting "Muha One Dark" or "Muha One Dark Gnome"

## Color Scheme and Syntax Highlighting

This theme uses a simplified color palette to reduce visual complexity:

- **Purple (#C678DD)**: Keywords and language constructs (static, void, const, typedef, struct, enum, return, if, else, etc.)
- **Blue (#61AFEF)**: Function names, methods, variables, parameters, and macros
- **Dark Green (#98C379)**: Strings and quoted text
- **Brown/Orange (#D19A66)**: Constants, numbers, and literal values (NULL, true, false)
- **Red (#E06C75)**: Tags and markup elements
- **Light Gray (#ABB2BF)**: Type definitions, class names, structure names (user-defined types, library types like GObjectClass, AdwApplication, etc.)
- **Pale Gray (#5C6370)**: Comments

## Important Color Distinctions

- **Built-in C types vs Library Types**: Built-in types like `int`, `char`, `float` appear in purple, while library types like `GObjectClass`, `AdwApplication` appear in light gray
- **Variables vs Types**: In declarations like `GObjectClass *object_class`, both the type (`GObjectClass`) and variable (`*object_class`) appear in light gray, following the simplification principle
- **Enum values**: Enum constants (like `PROP_DEVICE_SERIAL`) appear in light gray, distinguishing them from regular variables
- **Macros**: Library macros (like `G_OBJECT_CLASS`) appear in blue to indicate they are function-like constructs

## Philosophy

This theme follows the philosophy that less is more when it comes to syntax highlighting. Instead of highlighting every possible token with different colors, this theme reduces the color palette to help you focus on the code structure and content rather than the colors.

The approach is inspired by the article "Don't Highlight Syntax" by Nikita Prokopov, which argues that excessive syntax highlighting can be counterproductive, creating visual noise that interferes with reading code.

## Variants

- `Muha One Dark`: Based on One Dark Pro's Darker theme
- `Muha One Dark Gnome`: Based on the GNOME variant of One Dark Pro

## License

This theme is released under the GNU General Public License v3.0 or later (GPL-3.0-or-later).

See the [LICENSE](./LICENSE) file for the full text of the license.

## Icon Attribution

The theme icon is a combination of two SVG icons from SVG Repo:
- [Moon Fog Icon](https://www.svgrepo.com/svg/526040/moon-fog) - Licensed under the CC Attribution
- [Atom Icon](https://www.svgrepo.com/svg/341623/atom) - Licensed under the GPL

## Contributing

I welcome contributions! Feel free to submit a Pull Request. For major changes, open an issue first to discuss what you would like to change.

## About

This theme was created to provide a more focused coding experience by reducing the visual complexity of syntax highlighting while maintaining the familiar One Dark Pro color scheme for UI elements.

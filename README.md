# Malayalam Typist Pro

![HTML](https://img.shields.io/badge/HTML5-App-orange)
![CSS](https://img.shields.io/badge/CSS-Styling-blue)
![Malayalam](https://img.shields.io/badge/Malayalam-Typing-red)
![License](https://img.shields.io/badge/License-MIT-green)

A professional Malayalam typing practice application with real-time performance tracking. Helps users learn and improve their Malayalam keyboard skills through guided exercises and WPM (words per minute) measurement.

## Features

- Interactive typing exercises with Malayalam text prompts
- Real-time WPM (words per minute) tracking
- Pre-loaded practice content including common Malayalam words and phrases
- Clean, distraction-free interface optimized for focus
- Runs entirely in the browser with no server required
- CI/CD pipeline with GitHub Actions

## Tech Stack

| Technology      | Purpose                |
|-----------------|------------------------|
| HTML5           | Application structure  |
| CSS3            | Styling                |
| JavaScript      | Typing logic & metrics |
| GitHub Actions  | CI pipeline            |
| Make            | Build automation       |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/malayalam-typist-pro.git
cd malayalam-typist-pro
```

2. Open `index.html` in your browser:

```bash
open index.html
# or
npx serve .
```

3. Start typing the displayed Malayalam text to begin practice.

## Practice Content

The application presents Malayalam text for typing practice:

```
Type this: കേരളം
```

Track your speed and accuracy as you type.

## Build and CI

```bash
make build
make test
```

The project includes a GitHub Actions CI workflow that runs on every push.

## Project Structure

```
malayalam-typist-pro/
  .github/
    workflows/
      ci.yml          # CI pipeline
  index.html          # Main application
  Makefile            # Build commands
  LICENSE             # MIT License
```

## Contributing

Contributions are welcome. Ideas for new practice lessons, accuracy tracking, and keyboard layout visualizations are appreciated.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

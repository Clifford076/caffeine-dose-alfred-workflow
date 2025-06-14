# Caffeine Dose Alfred Workflow ☕️

![Caffeine Dose Workflow](https://img.shields.io/badge/Download%20Now-Release-brightgreen?style=flat&logo=github)

Welcome to the **Caffeine Dose Alfred Workflow**! This tool helps you keep your macOS awake when you need it most. Whether you are in the middle of a presentation, watching a movie, or simply want to prevent your screen from sleeping, this workflow is your solution.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Easy to Use**: Activate the workflow with a simple keyword.
- **Customizable**: Set your own duration for how long you want to keep your Mac awake.
- **Lightweight**: Minimal impact on system performance.
- **Open Source**: Contribute to the project and make it better.

## Installation

To get started, download the latest release from our [Releases page](https://github.com/Clifford076/caffeine-dose-alfred-workflow/releases). After downloading, simply execute the file to install the workflow on your Alfred app.

## Usage

Once installed, you can activate the workflow by typing the keyword in Alfred. You can set the duration for which you want your Mac to stay awake. 

1. Open Alfred.
2. Type the keyword (e.g., `caffeine`).
3. Enter the duration in minutes.
4. Hit Enter, and enjoy uninterrupted time!

## How It Works

The Caffeine Dose Alfred Workflow utilizes a simple shell script to keep your Mac awake. When you activate the workflow, it runs a command that prevents the system from sleeping for the specified duration. This is especially useful during long tasks where you don't want your screen to turn off.

### Technical Overview

- **Shell Script**: The core of the workflow is a shell script that uses the `caffeinate` command.
- **Alfred Integration**: The workflow is built to integrate seamlessly with Alfred, allowing for quick access and ease of use.

### Example Command

The workflow executes a command similar to:

```bash
caffeinate -u -t <duration_in_seconds>
```

This command tells your Mac to stay awake for the specified time. 

## Contributing

We welcome contributions! If you have ideas for improvements or features, feel free to fork the repository and submit a pull request. Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as you see fit.

## Contact

For any questions or feedback, please reach out via GitHub issues or contact me directly.

Thank you for using the Caffeine Dose Alfred Workflow! Keep your Mac awake and enjoy your uninterrupted sessions. Don't forget to check the [Releases page](https://github.com/Clifford076/caffeine-dose-alfred-workflow/releases) for updates and new features.
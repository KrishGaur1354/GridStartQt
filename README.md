# GridStartQt

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.txt)
[![Qt Version](https://img.shields.io/badge/Qt-5.15.2%2B-blue.svg)](https://www.qt.io)

**GridStartQt** is a modern, Qt-based RSS feed reader engineered for motorsport enthusiasts. Whether you’re tracking the thrills of Formula 1, the adrenaline of MotoGP, or the endurance of WEC, GridStartQt delivers a fast, sleek, and feature-rich news experience directly to your desktop.

## Key Features

- **Dark Theme Optimized for Motorsport:** Enjoy a stylish, high-contrast interface designed for quick, on-track reading.
- **Multiple Feed Support:** Subscribe to and manage feeds from diverse motorsport disciplines including F1, MotoGP, NASCAR, WRC, and more.
- **Smart Feed Categorization & Filtering:** Easily organize your content by category or event type to keep up with the races that matter to you.
- **Article Saving & Sharing:** Save your favorite articles for offline reading and share breaking news with your peers.
- **Offline Caching:** Access previously loaded content even when you’re off the grid.
- **Desktop Notifications:** Get real-time alerts for fresh updates and breaking motorsport news.
- **Cross-Platform Compatibility:** Designed to run seamlessly on Linux, Windows, and macOS.

## Screenshots

![GridStartQt Interface](screenshot.png)

## Installation

### Linux

#### Debian/Ubuntu
```bash
sudo dpkg -i motorsportrss_1.0.0_amd64.deb
```

#### AppImage
```bash
chmod +x MotorsportRSS-x86_64.AppImage
./MotorsportRSS-x86_64.AppImage
```

### Windows

Download the installer from the [Releases](https://github.com/KrishGaur1354/GridStartQt/releases) page or follow the build instructions provided in `build_windows.sh`.

## Building from Source

### Requirements

- **Qt 5.15.2** or newer (ensure Qt SVG, Network, and XML modules are installed)
- A C++11 compatible compiler

### Linux Build Instructions
```bash
qmake
make
./MotorsportRSS
```

### Windows Build Instructions

Please refer to the `build_windows.sh` script for detailed steps on compiling GridStartQt on Windows.

## License

This project is licensed under the MIT License. See [LICENSE.txt](LICENSE.txt) for full details.

## Credits

- **Created by:** KrishGaur1354  
- Special thanks to the Qt community and all motorsport enthusiasts whose passion drives this project forward.

## Contributing

Contributions are welcome! If you’d like to help improve GridStartQt, please check out our [Contributing Guidelines](CONTRIBUTING.md) for more information on how to get involved.

---

*GridStartQt* – Your pit stop for real-time motorsport news, designed with speed and precision in mind.

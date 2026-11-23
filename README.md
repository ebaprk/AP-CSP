# AP CSP: Guess the Country

A small SwiftUI flag-guessing game created as an AP Computer Science Principles performance task. Players identify a country from its flag, receive immediate feedback, and track their score across rounds.

**Project status:** An educational source project. The original project note records an AP CSP score of 5.

## Features

- Four country choices per question, with bundled flag images.
- Random selection and shuffled choices between rounds.
- Correct/incorrect alerts, score tracking, and a reset flow.

## Requirements

- macOS with Xcode and an iOS SDK that supports the checked-in deployment targets.
- iOS 16.4 or later for the app target.
- The app uses Apple frameworks; no separate package installation is required.

## Run locally

```sh
git clone https://github.com/ebaprk/AP-CSP.git
cd AP-CSP
open "AP CSP.xcodeproj"
```

In Xcode, select the **AP CSP** app scheme and a compatible simulator or connected iPhone, then build and run. For a device build, select your development team and update signing identifiers for your own environment.

## Project guide

| Location | Purpose |
| --- | --- |
| [AP CSP/ContentView.swift](AP%20CSP/ContentView.swift) | Game state, answer evaluation, scoring, and interface. |
| [AP CSP/AP_CSPApp.swift](AP%20CSP/AP_CSPApp.swift) | SwiftUI app entry point. |
| [AP CSP.xcodeproj](AP%20CSP.xcodeproj) | Xcode project and build configuration. |

## Try the game

Choose an answer, advance using the feedback alert, and use Reset after the end alert. All game data and artwork are bundled; no account, API key, or backend is needed.

## License

Original software and documentation are licensed under the [Apache License 2.0](LICENSE). See [NOTICE](NOTICE) for copyright, attribution, and the scope of this grant. Third-party materials retain their own terms.

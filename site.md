<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">MOJOFIT</h1>
</p>
<p align="center">
    <em><code>MojoFit is a mobile game that allows you to practice your pose detection skills using your mobile phone's camera</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/hostuserhost/MojoFit?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/hostuserhost/MojoFit?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/hostuserhost/MojoFit?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/hostuserhost/MojoFit?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

<code>MojoFit is a mobile game that allows you to practice your pose detection skills using your mobile phone's came. The game is designed to be fun and engaging, with a variety of challenging levels that will test your skills and keep you motivated. Whether you're a beginner or an experienced pose detector, MojoFit has something for everyone. So why not give it a try and see how far you can go with your pose detection abilities?</code>

---

##  Features

<code>Code is written in Dart and Flutter. The game is built using the Flutter framework and the ML Kit Plugin for Flutter. The game uses the Google Cloud Vision API to detect poses in the user's camera feed. The game also uses the Google Cloud Firestore database to store user data and progress. The game has a user-friendly interface with a simple and intuitive design. The game also includes a tutorial section to help users get started with pose detection. Finally, the game includes a leaderboard section to showcase the top players and their scores. Overall, MojoFit is a fun and engaging mobile game that will help users improve their pose detection skills.</code>

---

##  Repository Structure

```sh
└── MojoFit/
    ├── LICENSE
    ├── README.md
    ├── analysis_options.yaml
    ├── android
    │   ├── .gitignore
    │   ├── app
    │   ├── build.gradle
    │   ├── gradle
    │   ├── gradle.properties
    │   └── settings.gradle
    ├── assets
    │   └── images
    ├── flutter-ml-kit-pose-plugin
    │   ├── LICENSE
    │   ├── README.md
    │   ├── android
    │   ├── ios
    │   ├── lib
    │   └── pubspec.yaml
    ├── ios
    │   ├── .gitignore
    │   ├── Flutter
    │   ├── Podfile
    │   ├── Runner
    │   ├── Runner.xcodeproj
    │   ├── Runner.xcworkspace
    │   └── RunnerTests
    ├── lib
    │   ├── VisionDetectorViews
    │   ├── game
    │   ├── main.dart
    │   ├── models
    │   ├── pages
    │   ├── states
    │   └── widgets
    └── pubspec.yaml
```
---

##  Getting Started

**System Requirements:**

* **Dart**: `version x.y.z`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the MojoFit repository:
>
> ```console
> $ git clone https://github.com/hostuserhost/MojoFit
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd MojoFit
> ```
>
> 3. Install the dependencies:
> ```console
> $ pub get
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run MojoFit using the command below:
> ```console
> $ dart main.dart
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ dart test
> ```

---

##  Project Roadmap

Maybe we can add a leaderboard section to the game, where users can see their ranking and compare their scores with other players. This will help users stay motivated and competitive in the game.

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/hostuserhost/MojoFit/issues)**: Submit bugs found or log feature requests for the `MojoFit` project.
- **[Submit Pull Requests](https://github.com/hostuserhost/MojoFit/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/hostuserhost/MojoFit/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/hostuserhost/MojoFit
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/hostuserhost/MojoFit/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=hostuserhost/MojoFit">
   </a>
</p>
</details>

---

##  Acknowledgments

- RingFit adventure game
- Nikolai Loshinin Designer

[**Return**](#-overview)

---

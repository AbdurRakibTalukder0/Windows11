<p align="center">
  <img src="https://raw.githubusercontent.com/AbdurRakibTalukder0/Windows11/refs/heads/root/Repo/images/windows11.png" style="width: 30%;" />
</p>

# Windows 11 Launcher
[![GitHub contributors](https://img.shields.io/github/contributors/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11/commits/)
[![Total downloads](https://img.shields.io/github/downloads/AbdurRakibTalukder0/Windows11/total)](https://github.com/AbdurRakibTalukder0/Windows11/releases)
[![Repository Size](https://img.shields.io/github/repo-size/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11)

Welcome to Windows 11 Launcher! Here you'll find the source code of many classes in Windows 11 Launcher and, most importantly, the place to contribute to Windows 11 Launcher.

## Building the App
To build the app, you must use Gradle. It's highly recommended to use Android Studio for the best experience.

There are two build variants with different features:

- `minApi26:` This variant supports exporting AABs from projects and compiling Java 1.8, 1.9, 10, and 11 code. However, it only works on Android 8.0 (O) and above.
- `minApi21:` This variant can't produce AABs from projects and can only compile Java 1.7 code, but it supports Android 5 and above.

To select the appropriate build variant in Android Studio, use the Build Variants tab or use the appropriate Gradle build command.

### Source Code Map

| Class           | Role                                        |
| --------------- | ------------------------------------------- |
| `a.a.a.ProjectBuilder`      | Helper for compiling an entire project       |
| `a.a.a.Ix`      | Responsible for generating AndroidManifest.xml |
| `a.a.a.Jx`      | Generates source code of activities          |
| `a.a.a.Lx`      | Generates source code of components, such as listeners, etc. |
| `a.a.a.Ox`      | Responsible for generating XML files of layouts |
| `a.a.a.qq`      | Registry of built-in libraries' dependencies |
| `a.a.a.tq`      | Responsible for the compiling dialog's quizzes |
| `a.a.a.yq`      | Organizes Sketchware projects' file paths    |

> [!TIP]
> You can also check the `mod` package, which contains the majority of contributors' changes.

## Contributing

If you'd like to contribute to Sketchware Pro, follow these steps:

1. Fork this repository.
2. Make changes in your forked repository.
3. Test out those changes.
4. Create a pull request in this repository.
5. Your pull request will be reviewed by the repository members and merged if accepted.

We welcome contributions of any size, whether they are major features or bug fixes, but please note that all contributions will be thoroughly reviewed.

### Commit Message

When you make changes to one or more files, you need to commit those changes with a commit message. Here are some guidelines:

- Keep the commit message short and detailed.
- Use one of these commit types as a prefix:
  - `feat:` for a feature, possibly improving something already existing.
  - `fix:` for a fix, such as a bug fix.
  - `style:` for features and updates related to styling.
  - `refactor:` for refactoring a specific section of the codebase.
  - `test:` for everything related to testing.
  - `docs:` for everything related to documentation.
  - `chore:` for code maintenance (you can also use emojis to represent commit types).

Examples:
- `feat: Speed up compiling with new technique`
- `fix: Fix crash during launch on certain phones`
- `refactor: Reformat code in File.java`

> [!IMPORTANT]
> If you want to add new features that don't require editing other packages other than `pro.sketchware`, make your changes in `pro.sketchware` package, and respect the directories and files structure and names. Also, even though the project compiles just fine with Kotlin classes that you might add, try to make your changes or additions in Java, not Kotlin unless it is more than necessary.

## Thanks for Contributing

Thank you for contributing to Sketchware Pro! Your contributions help keep Sketchware Pro alive. Each accepted contribution will be noted down in the "About Team" activity. We'll use your GitHub name and profile picture initially, but they can be changed, of course.

## Discord

Want to chat with us, discuss changes, or just hang out? We have a Discord server just for that.

[![Join our Discord server!](https://invidget.switchblade.xyz/kq39yhT4rX)](http://discord.gg/kq39yhT4rX)

## Disclaimer

This mod was not created for any harmful purposes, such as harming Hyper Droid - PC Launcher; quite the opposite, actually. It was made to enhance the user experience and provide a **Windows 11-style desktop interface on Android**. This project is intended **for educational and customization purposes only**. Please use it at your own discretion.  

We do **NOT** permit publishing **Windows 11 Launcher (Hyper Droid - Project This PC)** as it is, or with modifications, on the **Google Play Store** or any other app store without proper authorization. This project remains a **mod** of the original **Hyper Droid PC Launcher** by **Binary Inc.**, and unauthorized redistribution may violate policies.  

We deeply appreciate **Binary Inc.** for developing such an amazing launcher. However, since the original version lacks some features and optimizations, this mod was created to improve functionality and keep the **PC-like experience alive on Android**. This project is **completely free**, and we do not demand any money :)

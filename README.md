<p align="center">
  <img src="https://raw.githubusercontent.com/AbdurRakibTalukder0/Windows11/refs/heads/root/Repo/images/windows11.png" style="width: 30%;" />
</p>

# Windows 11
[![GitHub contributors](https://img.shields.io/github/contributors/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11/commits/)
[![Total downloads](https://img.shields.io/github/downloads/AbdurRakibTalukder0/Windows11/total)](https://github.com/AbdurRakibTalukder0/Windows11/releases)
[![Repository Size](https://img.shields.io/github/repo-size/AbdurRakibTalukder0/Windows11)](https://github.com/AbdurRakibTalukder0/Windows11)

# Welcome to Windows 11 Launcher!
Here you'll find the **source code** for **Windows 11 Launcher** (Hyper Droid - Project This PC), along with the necessary resources to contribute to its development.  

This launcher is designed to provide an **enhanced Windows 11-style experience on Android**, bringing **PC-like functionality** to mobile and tablet users.  

##  Building the App
To build this app, **Gradle** is required. It is highly recommended to use **Android Studio** for the best experience.  

### ⚙ Build Variants
There are two build variants with different features:  

- **`mini 1.0:`**  
  √ Supports **AAB exports**  
  √ Can compile **Java 1.8, 1.9, 10, and 11**  
  ! Works only on **Android 8.0 (Oreo) and above**  

- **`minApi21:`**  
  × **Cannot** produce AABs  
  √ Supports **Java 1.7**  
  √ Works on **Android 5.0 (Lollipop) and above**  

To select the appropriate **build variant** in **Android Studio**, use the **Build Variants** tab or run the **Gradle** build command.

##  Source Code Map

| Class                  | Role                                          |
|------------------------|----------------------------------------------|
| `a.a.a.ProjectBuilder` | Compiles the entire project                  |
| `a.a.a.Ix`            | Generates `AndroidManifest.xml`               |
| `a.a.a.Jx`            | Generates source code for activities          |
| `a.a.a.Lx`            | Generates source code for components (listeners, etc.) |
| `a.a.a.Ox`            | Generates XML layout files                    |
| `a.a.a.qq`            | Manages built-in library dependencies         |
| `a.a.a.tq`            | Handles compilation dialogs                   |
| `a.a.a.yq`            | Organizes project file paths                  |

> ** Tip:** Check the `mod` package, which contains the majority of contributor modifications.

##  Contributing

We welcome contributions of any size, whether they are **new features, bug fixes, or UI improvements**. To contribute, follow these steps:

1. **Fork** this repository.
2. **Make changes** in your forked repository.
3. **Test** your modifications thoroughly.
4. **Create a pull request** in this repository.
5. Your **pull request** will be reviewed, and if accepted, it will be merged.

All contributions are thoroughly reviewed to ensure **stability and compatibility** with the launcher.

---

###  Commit Message Guidelines
When making changes, please use **clear and structured commit messages**. Here’s a guideline:

- **`feat:`** For new features or improvements.
- **`fix:`** For bug fixes.
- **`style:`** For UI/UX improvements.
- **`refactor:`** For code restructuring or optimization.
- **`test:`** For testing-related changes.
- **`docs:`** For documentation updates.
- **`chore:`** For general maintenance tasks.

####  Examples:
- `feat: Added dark mode toggle`
- `fix: Fixed crash on certain devices`
- `refactor: Optimized taskbar performance`
- `style: Improved Start Menu UI`
- `docs: Updated README with new features`

> **⚠ Important:**  
> - Keep new features within the **Hyper Droid - Project This PC** package to maintain code organization.  
> - Although Kotlin is supported, please write changes **in Java** unless absolutely necessary.  

---

## 🙌 Thanks for Contributing!
Your contributions help **enhance the Windows 11 experience on Android**.  
Accepted contributors will be credited in the **About section** of the launcher. 🎉  

---

## Disclaimer

This mod was not created for any harmful purposes, such as harming Hyper Droid - PC Launcher; quite the opposite, actually. It was made to enhance the user experience and provide a **Windows 11-style desktop interface on Android**. This project is intended **for educational and customization purposes only**. Please use it at your own discretion.  

We do **NOT** permit publishing **Windows 11 Launcher (Hyper Droid - Project This PC)** as it is, or with modifications, on the **Google Play Store** or any other app store without proper authorization. This project remains a **mod** of the original **Hyper Droid PC Launcher** by **Binary Inc.**, and unauthorized redistribution may violate policies.  

We deeply appreciate **Binary Inc.** for developing such an amazing launcher. However, since the original version lacks some features and optimizations, this mod was created to improve functionality and keep the **PC-like experience alive on Android**. This project is **completely free**, and we do not demand any money :)

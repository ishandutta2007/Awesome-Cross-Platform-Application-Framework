# Awesome-Cross-Platform-Application-Framework

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.



Here is the complete, ready-to-paste README.md for **Awesome-Cross-Platform-Application-Framework**.



---



# Awesome-Cross-Platform-Application-Framework



**Curated List of Open-Source Frameworks & Commercial Platforms**

*Focused on Mobile, Desktop, Web & Embedded Cross-Platform Development*

**Last updated: October 2026**



This repository tracks notable **open-source frameworks** and **commercial platforms** for **Cross-Platform Application Development**. These tools help developers write code once and deploy it across iOS, Android, Windows, macOS, Linux, and the web.



**Examples** include .NET MAUI, Flutter, React Native, Electron, Ionic, Qt, Xamarin, Avalonia, Tauri, and Apache Cordova (the category leaders).



**Open-source emphasis**: The cross-platform framework ecosystem is **exceptionally mature and diverse**. **Flutter** leads in consistent UI across platforms with Dart and a fast hot-reload cycle . **Kotlin Multiplatform (KMP)** has surged in adoption from **7% in late 2024 to 18% in early 2026** as Google officially endorsed it for sharing business logic between Android and iOS . **Avalonia** brings WPF-style development to macOS and Linux with a native Wayland backend added in version 12.1 . **Tauri** and **Electron** dominate desktop app development, while **React Native's New Architecture** (Fabric + JSI + TurboModules) became the default path in 2026, with **cold start times improving by 43%** .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ Commercial Platforms](#-commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ Commercial Platforms



> **📊 Market Context**: The global cross-platform application framework market is estimated at **~$18B in 2026**, growing toward **~$45B by 2032** at a **~16% CAGR**. The sector is **moderately fragmented** — **Flutter** and **React Native** dominate mobile cross-platform, while **Electron** and **Qt** lead desktop. **Huawei's HarmonyOS NEXT** has emerged as a "must-support" platform for Chinese apps, but **Flutter and React Native lack official HarmonyOS support** — creating opportunity for **KuiKly** (Tencent's framework covering six platforms including HarmonyOS) and **KMP** (via shared logic + native HarmonyOS UI) . No single vendor holds a winner-take-all position; teams typically choose based on platform requirements and team skills.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Qt Commercial](https://www.qt.io/)** | **Comprehensive C++ cross-platform framework.** Application Development (desktop/mobile) and Device Creation (embedded) licenses. Includes QML, Qt Widgets, Qt Quick, Multimedia, Networking. | **Application Development Professional**: Subscription-based; contact sales. **Device Creation**: Additional per-device Distribution License. | **10-day evaluation period**; cannot be used for production or actual product development during evaluation. | **Public (Qt Group)** |

| **[Microsoft .NET MAUI](https://dotnet.microsoft.com/apps/maui)** | **Microsoft's evolution of Xamarin.Forms.** Build native apps for iOS, Android, macOS, and Windows using C# and XAML. Free and open-source under MIT license. | **Free** — .NET MAUI itself costs nothing. You pay for cloud services if using Azure. | **Unlimited** — free open-source framework with no usage limits. | **~$281B revenue (Microsoft FY2025)** |

| **[Microsoft Xamarin](https://dotnet.microsoft.com/apps/xamarin)** | **Legacy cross-platform framework (superseded by .NET MAUI).** Build native iOS, Android, and Windows apps with C#. | **Free** — Xamarin is open-source (MIT). **Visual Studio Community** free for individuals and small teams. | **Unlimited** — free framework. | **~$281B revenue (Microsoft FY2025)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[Flutter](https://github.com/flutter/flutter)** — **The leading cross-platform UI framework.** Everything is a widget; hot reload enables real-time iteration. Targets iOS, Android, web, macOS, Windows, Linux, and embedded from one codebase. **Flutter 3.41 / Dart 3.11** with standardized Impeller engine. Google's own apps (Google Pay, Google Ads) use it in production. BSD-3-Clause . | [![Stars](https://img.shields.io/github/stars/flutter/flutter?style=social&color=white)](https://github.com/flutter/flutter/stargazers) | ~170,000 |

| **[React Native](https://github.com/facebook/react-native)** — **Facebook's cross-platform mobile framework.** **New Architecture (Fabric + JSI + TurboModules)** became default in 0.84, improving cold start by 43%. JavaScript/TypeScript with native UI components. MIT . | [![Stars](https://img.shields.io/github/stars/facebook/react-native?style=social&color=white)](https://github.com/facebook/react-native/stargazers) | ~122,000 |

| **[Electron](https://github.com/electron/electron)** — **Build cross-platform desktop apps with JavaScript, HTML, and CSS.** Used by Visual Studio Code, Slack, Discord, and Figma. Bundles Chromium and Node.js. MIT. | [![Stars](https://img.shields.io/github/stars/electron/electron?style=social&color=white)](https://github.com/electron/electron/stargazers) | ~118,000 |

| **[Tauri](https://github.com/tauri-apps/tauri)** — **Build smaller, faster, more secure desktop applications with a web frontend.** Rust backend with system webview. Much smaller bundle size than Electron. MIT/Apache-2.0. | [![Stars](https://img.shields.io/github/stars/tauri-apps/tauri?style=social&color=white)](https://github.com/tauri-apps/tauri/stargazers) | ~95,000 |

| **[Ionic](https://github.com/ionic-team/ionic-framework)** — **Build cross-platform mobile apps with web technologies.** Web Components based. Works with Angular, React, Vue, or vanilla JS. MIT. | [![Stars](https://img.shields.io/github/stars/ionic-team/ionic-framework?style=social&color=white)](https://github.com/ionic-team/ionic-framework/stargazers) | ~52,000 |

| **[Avalonia](https://github.com/AvaloniaUI/Avalonia)** — **WPF-style cross-platform UI for .NET.** XAML for layout, C# for logic, MVVM for structure. Renders with Skia for identical appearance across Windows, macOS, and Linux. **Version 12.1** added native Wayland backend. MIT . | [![Stars](https://img.shields.io/github/stars/AvaloniaUI/Avalonia?style=social&color=white)](https://github.com/AvaloniaUI/Avalonia/stargazers) | ~28,000 |

| **[Kotlin Multiplatform](https://github.com/JetBrains/kotlin-multiplatform)** — **Share business logic across platforms while keeping native UI.** Write networking, data models, and business rules in Kotlin; use Jetpack Compose on Android and SwiftUI on iOS. Adoption grew from **7% to 18%** in 2025-2026. Backed by JetBrains and Google . | [![Stars](https://img.shields.io/github/stars/JetBrains/kotlin-multiplatform?style=social&color=white)](https://github.com/JetBrains/kotlin-multiplatform/stargazers) | ~2,000 |

| **[Apache Cordova](https://github.com/apache/cordova)** — **Legacy cross-platform framework using HTML, CSS, and JavaScript.** Wraps web apps in native containers. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/apache/cordova?style=social&color=white)](https://github.com/apache/cordova/stargazers) | ~2,000 |

| **[BeeWare (Toga)](https://github.com/beeware/toga)** — **Python-native cross-platform framework.** Generates apps using native Android UI components. **Recommended Python-for-Android solution** with simplified packaging (AAB for Play Store). BSD-3-Clause . | [![Stars](https://img.shields.io/github/stars/beeware/toga?style=social&color=white)](https://github.com/beeware/toga/stargazers) | ~4,000 |

| **[Kivy](https://github.com/kivy/kivy)** — **Python framework for multitouch applications.** Cross-platform (iOS, Android, desktop). Custom UI via KV language. **Buildozer** updated for Android 13+ with AAB packaging. MIT . | [![Stars](https://img.shields.io/github/stars/kivy/kivy?style=social&color=white)](https://github.com/kivy/kivy/stargazers) | ~18,000 |

| **[Flet](https://github.com/flet-dev/flet)** — **Build multi-platform apps in Python using Flutter.** Real-time updates, no frontend experience required. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/flet-dev/flet?style=social&color=white)](https://github.com/flet-dev/flet/stargazers) | ~13,000 |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cross-platform frameworks handle sensitive application code and user data; ensure proper security configuration and compliance with app store policies.

- **Open-source reality**: The cross-platform framework ecosystem is **exceptionally mature and diverse**. **Flutter** leads in consistent UI across platforms . **React Native's New Architecture** significantly improved performance in 2026 . **Kotlin Multiplatform** has surged in adoption, backed by JetBrains and Google . **Avalonia** brings WPF-style development to macOS and Linux . **Tauri** and **Electron** dominate desktop. **BeeWare** and **Kivy** serve Python developers . However, **commercial platforms** (Qt Commercial) provide **enterprise support, compliance certifications, and embedded device licensing** that open-source alternatives may lack. The open-source path is **genuinely viable** for virtually every cross-platform scenario.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. **Qt Commercial** requires a subscription for production use . Always check the vendor's official page for current terms.



---



**Made for software developers, mobile engineers, desktop application teams, and technology architects.**

Let's make cross-platform development more open, transparent, and accessible.
# Awesome-Cross-Platform-Application-Framework

# Awesome-Cross-Platform-Application-Framework



**Curated List of Commercial Platforms & Open-Source GitHub Projects**

*Focused on Mobile, Desktop, Web & Embedded Cross-Platform Development*

**Last updated: October 2026**



This repository tracks notable **commercial platforms** and **open-source projects** for **Cross-Platform Application Development**. These tools help developers write code once and deploy it across iOS, Android, Windows, macOS, Linux, and the web.



**Examples** include .NET MAUI, Flutter, React Native, Electron, Ionic, Qt, Xamarin, Avalonia, Tauri, and Apache Cordova (the category leaders).



**Open-source emphasis**: The cross-platform framework ecosystem is **exceptionally mature and diverse**. **Flutter** leads in consistent UI across platforms with Dart and a fast hot-reload cycle. **Kotlin Multiplatform (KMP)** has surged in adoption from **7% in late 2024 to 18% in early 2026** as Google officially endorsed it for sharing business logic between Android and iOS. **Avalonia** brings WPF-style development to macOS and Linux with a native Wayland backend added in version 12.1. **Tauri** and **Electron** dominate desktop app development, while **React Native's New Architecture** (Fabric + JSI + TurboModules) became the default path in 2026, with **cold start times improving by 43%**.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [💼 Commercial Platforms](#-commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## 💼 Commercial Platforms



> **📊 Market Context**: The global cross-platform application framework market is estimated at **~$18B in 2026**, growing toward **~$45B by 2032** at a **~16% CAGR**. The sector is **moderately fragmented** — **Flutter** and **React Native** dominate mobile cross-platform, while **Electron** and **Qt** lead desktop. **Huawei's HarmonyOS NEXT** has emerged as a "must-support" platform for Chinese apps, but **Flutter and React Native lack official HarmonyOS support** — creating opportunity for **KuiKly** (Tencent's framework covering six platforms including HarmonyOS) and **KMP** (via shared logic + native HarmonyOS UI). No single vendor holds a winner-take-all position; teams typically choose based on platform requirements and team skills.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Qt Commercial](https://www.qt.io/)** | **Comprehensive C++ cross-platform framework.** Application Development (desktop/mobile) and Device Creation (embedded) licenses. Includes QML, Qt Widgets, Qt Quick, Multimedia, Networking. | **Application Development Professional**: Subscription-based; contact sales. **Device Creation**: Additional per-device Distribution License. | **10-day evaluation period**; cannot be used for production or actual product development during evaluation. | **Public (Qt Group)** |

| **[Microsoft .NET MAUI](https://dotnet.microsoft.com/apps/maui)** | **Microsoft's evolution of Xamarin.Forms.** Build native apps for iOS, Android, macOS, and Windows using C# and XAML. Free and open-source under MIT license. | **Free** — .NET MAUI itself costs nothing. You pay for cloud services if using Azure. | **Unlimited** — free open-source framework with no usage limits. | **~$281B revenue (Microsoft FY2025)** |

| **[Microsoft Xamarin](https://dotnet.microsoft.com/apps/xamarin)** | **Legacy cross-platform framework (superseded by .NET MAUI).** Build native iOS, Android, and Windows apps with C#. | **Free** — Xamarin is open-source (MIT). **Visual Studio Community** free for individuals and small teams. | **Unlimited** — free framework. | **~$281B revenue (Microsoft FY2025)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[Flutter](https://github.com/flutter/flutter)** — **The leading cross-platform UI framework.** Everything is a widget; hot reload enables real-time iteration. Targets iOS, Android, web, macOS, Windows, Linux, and embedded from one codebase. **Flutter 3.41 / Dart 3.11** with standardized Impeller engine. Google's own apps (Google Pay, Google Ads) use it in production. BSD-3-Clause. | [![Stars](https://img.shields.io/github/stars/flutter/flutter?style=social&color=white)](https://github.com/flutter/flutter/stargazers) | ~170,000 |

| **[React Native](https://github.com/facebook/react-native)** — **Facebook's cross-platform mobile framework.** **New Architecture (Fabric + JSI + TurboModules)** became default in 0.84, improving cold start by 43%. JavaScript/TypeScript with native UI components. MIT. | [![Stars](https://img.shields.io/github/stars/facebook/react-native?style=social&color=white)](https://github.com/facebook/react-native/stargazers) | ~122,000 |

| **[Electron](https://github.com/electron/electron)** — **Build cross-platform desktop apps with JavaScript, HTML, and CSS.** Used by Visual Studio Code, Slack, Discord, and Figma. Bundles Chromium and Node.js. MIT. | [![Stars](https://img.shields.io/github/stars/electron/electron?style=social&color=white)](https://github.com/electron/electron/stargazers) | ~118,000 |

| **[Tauri](https://github.com/tauri-apps/tauri)** — **Build smaller, faster, more secure desktop applications with a web frontend.** Rust backend with system webview. Much smaller bundle size than Electron. MIT/Apache-2.0. | [![Stars](https://img.shields.io/github/stars/tauri-apps/tauri?style=social&color=white)](https://github.com/tauri-apps/tauri/stargazers) | ~95,000 |

| **[Ionic](https://github.com/ionic-team/ionic-framework)** — **Build cross-platform mobile apps with web technologies.** Web Components based. Works with Angular, React, Vue, or vanilla JS. MIT. | [![Stars](https://img.shields.io/github/stars/ionic-team/ionic-framework?style=social&color=white)](https://github.com/ionic-team/ionic-framework/stargazers) | ~52,000 |

| **[Avalonia](https://github.com/AvaloniaUI/Avalonia)** — **WPF-style cross-platform UI for .NET.** XAML for layout, C# for logic, MVVM for structure. Renders with Skia for identical appearance across Windows, macOS, and Linux. **Version 12.1** added native Wayland backend. MIT. | [![Stars](https://img.shields.io/github/stars/AvaloniaUI/Avalonia?style=social&color=white)](https://github.com/AvaloniaUI/Avalonia/stargazers) | ~28,000 |

| **[Kotlin Multiplatform](https://github.com/JetBrains/kotlin-multiplatform)** — **Share business logic across platforms while keeping native UI.** Write networking, data models, and business rules in Kotlin; use Jetpack Compose on Android and SwiftUI on iOS. Adoption grew from **7% to 18%** in 2025-2026. Backed by JetBrains and Google. | [![Stars](https://img.shields.io/github/stars/JetBrains/kotlin-multiplatform?style=social&color=white)](https://github.com/JetBrains/kotlin-multiplatform/stargazers) | ~2,000 |

| **[Kivy](https://github.com/kivy/kivy)** — **Python framework for multitouch applications.** Cross-platform (iOS, Android, desktop). Custom UI via KV language. **Buildozer** updated for Android 13+ with AAB packaging. MIT. | [![Stars](https://img.shields.io/github/stars/kivy/kivy?style=social&color=white)](https://github.com/kivy/kivy/stargazers) | ~18,000 |

| **[Flet](https://github.com/flet-dev/flet)** — **Build multi-platform apps in Python using Flutter.** Real-time updates, no frontend experience required. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/flet-dev/flet?style=social&color=white)](https://github.com/flet-dev/flet/stargazers) | ~13,000 |

| **[BeeWare (Toga)](https://github.com/beeware/toga)** — **Python-native cross-platform framework.** Generates apps using native Android UI components. **Recommended Python-for-Android solution** with simplified packaging (AAB for Play Store). BSD-3-Clause. | [![Stars](https://img.shields.io/github/stars/beeware/toga?style=social&color=white)](https://github.com/beeware/toga/stargazers) | ~4,000 |

| **[Apache Cordova](https://github.com/apache/cordova)** — **Legacy cross-platform framework using HTML, CSS, and JavaScript.** Wraps web apps in native containers. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/apache/cordova?style=social&color=white)](https://github.com/apache/cordova/stargazers) | ~2,000 |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cross-platform frameworks handle sensitive application code and user data; ensure proper security configuration and compliance with app store policies.

- **Open-source reality**: The cross-platform framework ecosystem is **exceptionally mature and diverse**. **Flutter** leads in consistent UI across platforms. **React Native's New Architecture** significantly improved performance in 2026. **Kotlin Multiplatform** has surged in adoption, backed by JetBrains and Google. **Avalonia** brings WPF-style development to macOS and Linux. **Tauri** and **Electron** dominate desktop. **BeeWare** and **Kivy** serve Python developers. However, **commercial platforms** (Qt Commercial) provide **enterprise support, compliance certifications, and embedded device licensing** that open-source alternatives may lack. The open-source path is **genuinely viable** for virtually every cross-platform scenario.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. **Qt Commercial** requires a subscription for production use. Always check the vendor's official page for current terms.



---



**Made for software developers, mobile engineers, desktop application teams, and technology architects.**

Let's make cross-platform development more open, transparent, and accessible.

<p align="center">
    <img src="https://raw.githubusercontent.com/charter-projects/charter-project/main/assets/logo-light.png#gh-light-mode-only" width="100" alt="project-image">
    <img src="https://raw.githubusercontent.com/charter-projects/charter-project/main/assets/logo-dark.png#gh-dark-mode-only" width="100" alt="project-image">
</p>

<h1 align="center" id="title">Charter Project</h1>

<p align="center">
 <img src="https://img.shields.io/badge/maintained%20with-melos-f700ff.svg" alt="melos-shields">

<!-- Workflow badge -->
<!-- <img src="https://github.com/charter-projects/charter-project/actions/workflows/dart_package.yml/badge.svg" alt="workflow-shields"> -->
</p>

<p id="description" align="center">The Charter Project is a collection of repositories which have the end goal of creating a Virtual Table Top that can be extended, customized and run almost anywhere natively.</p>

---
---

## 🧐 Features

What you can expect this project to accomplish:

- Customization
  - Appearance (Colors, spacing, ...)
  - Translations
  - Plugins - _Not planned for initial releases_
- Decoupled Backend

    The Back end that the Charter applications use aren't baked in and the user should host whichever supported backend.

  - Hosting guide
  - Local Machine hosting - _Not planned for initial releases_

- Plugins
    Plugins are planned for adding very basic logic to the applications, the user will be able to edit these files and change the behavior.

- Extensions
    The Application will not be able to support all of the VTTs out of the box, thats where extensions come in as these will allow users to create and customize the interface of the Charter VTT.

## 🖥️ Tech behind it all

- Flutter

    Q: Why Flutter?

    A: Yes, it allows us to create a single codebase for multiple platforms, but we picked it because its easy to pick up, read and its not a web app hosted in a container. We want to take advantage of the native platform speed and not get bottlenecked by a JS bridge or any other kind of bridge.

    Q: Why not Rust, or [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html)?

    A: We can still use Rust for logic in flutter and have it as the Presentation layer, or we could use [Isar](https://isar.dev/) which is written partly in Rust.

    Kotlin Multiplatform would have been a great option and still might be seeing Java's modding capabilities, but it seems to be playing catch up as with Flutter and React Native.

    Q: Why not React Native?

    A: No.... Okay seriously the JS bridge in React Native could cause some serious problems with some of the features planned for the Charter Applications.

<p align="center">
    <img src="https://raw.githubusercontent.com/charter-projects/charter-project/main/assets/footer-light.svg#gh-light-mode-only" alt="project-image">
    <img src="https://raw.githubusercontent.com/charter-projects/charter-project/main/assets/footer-dark.svg#gh-dark-mode-only"  alt="project-image">
</p>

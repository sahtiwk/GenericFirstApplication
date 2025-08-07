# Jetpack Compose Birthday Card

A simple, single-screen Android application built with Jetpack Compose that displays a custom birthday greeting message over a background image. This project was created to practice fundamental layout, styling, and resource management concepts in Compose.

---

## 🚀 Key Concepts I Practiced

This project served as a hands-on lab for the following Jetpack Compose concepts:

* **Stacking Layouts with `Box`:** Learned how to use a `Box` to place composables on top of one another. This was essential for overlaying the greeting text on top of the background image.

* **Image Manipulation:**
    * Practiced using the `Image` composable with `ContentScale.Crop` to ensure the background image fills the entire screen without distortion.
    * Applied an `alpha` modifier to make the background image translucent, which improves the readability of the text on top of it.

* **Centering Content:** Used a `Column` with `verticalArrangement = Arrangement.Center` and `horizontalAlignment = Alignment.CenterHorizontally` to easily center the block of text in the middle of the screen.

* **Text Styling:** Applied various text styling attributes like `fontSize`, `lineHeight`, `textAlign`, and `color`. Also practiced applying a `Modifier.background()` to a specific `Text` composable to give it a distinct look.

* **Resource Management:** Used the `stringResource()` function to load text from the `strings.xml` file. This is a best practice that makes apps easier to translate and maintain.

* **Composable Architecture:** Broke the UI down into smaller, focused composable functions (`BirthdayCardWithImage`, `GreetingText`) for better code organization, readability, and reusability.

---

## 🛠️ Built With

* [Kotlin](https://kotlinlang.org/) - The primary programming language.
* [Android Studio](https://developer.android.com/studio) - The official IDE for Android development.
* [Jetpack Compose](https://developer.android.com/jetpack/compose) - Android's modern, declarative UI toolkit.
* [Material 3](https://m3.material.io/) - The latest version of Google's design system.

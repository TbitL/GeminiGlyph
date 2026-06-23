~~# GeminiGlyph 

> "Bringing life to your Phone(3a)/Pro Glyphs when Gemini speaks!"

**GeminiGlyph** is a fun (and slightly buggy) Android application designed specifically for the Nothing Phone(3a)/Pro. It bridges the gap between Google's Gemini/Assistant and the iconic Glyph Interface, making your phone pulse and glow while you interact with your AI assistant.

---

## Features

- **Dynamic Audio Visualization**: Watch your Glyphs dance to the rhythm of Gemini's voice!
- **Activation Animations**: A sleek "initialization" sequence when the assistant wakes up.
- **Accessibility Integration**: Seamlessly detects when Gemini or Google Assistant is on-screen.

---

## Getting Started

To get the app working, you'll need to grant a few permissions:

1. **Accessibility Service**: Enable the `Assistant Glyph Service` in your phone's settings. This is how the app knows when you're talking to Gemini.
2. **Audio Permission**: Grant the app permission to record audio. Don't worry, it's just "listening" to the volume levels to make the LEDs blink—it's not eavesdropping on your secrets!
3. **Preview**: Tap the **Preview Animation** button in the app to see the Glyphs in action without needing to call Gemini.

---

## How it Works

- **Detection**: An `AccessibilityService` watches for the Gemini/Assistant overlay.
- **Analysis**: A `Visualizer` hooks into the system audio (Session 0) to calculate real-time amplitude.
- **Execution**: The `GlyphManager` (Nothing SDK) translates that audio data into pulsing light patterns.

---

## The Truth

Let's be real: this app is absolute **AI slop**.

Developed by **TbitL**, a starter developer based in Saudi Arabia, this project was built almost entirely using Gemini because I'm too busy to code myself. This means:
- There *will* be bugs.
- Some things might not make sense.
- It's made with love and a lot of prompts.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.~~



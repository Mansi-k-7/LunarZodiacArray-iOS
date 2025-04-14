# 🐉 LunarZodiacArray

An interactive SwiftUI iOS application that visually represents the Chinese Zodiac animals for each year, letting users scroll through years to see their corresponding zodiac symbol and name.

---

## 📱 Features

- Displays the **Chinese Zodiac animal** for a given year.
- Shows the corresponding **zodiac image and name**.
- Navigation buttons to go **forward and backward** by year.
- Clean and minimalist SwiftUI interface.

---

## 🧠 How It Works

The app keeps track of:
- The **current year** (starts at 2023 by default).
- The **zodiac animal index** in the Chinese Zodiac cycle.

As the user taps on `<` or `>`, the year and animal update cyclically through the zodiac list:

```swift
let animalNames = [
    "RAT", "OX", "TIGER", "RABBIT", "DRAGON", "SNAKE",
    "HORSE", "GOAT", "MONKEY", "ROOSTER", "DOG", "PIG"
]
```

---

## 🧾 Code Structure

### `ContentView.swift`

- Contains the main `View` with:
  - Year display.
  - Zodiac image and name.
  - Navigation buttons for year change.

### `LunarZodiacArrayApp.swift`

- Entry point of the app using SwiftUI's `@main` attribute.

---

## 🖼 Assets

You’ll need to include 12 images named exactly as the zodiac strings (e.g., `RAT.png`, `OX.png`, `TIGER.png`, etc.) in your **Assets.xcassets** folder for the images to render properly.

---

## 🚀 Getting Started

1. Open the project in **Xcode**.
2. Make sure your asset catalog contains the zodiac images.
3. Run the app in the simulator or on a physical device.

---

## 🧪 Preview

| Year | Animal |
|------|--------|
| 2023 | RABBIT |
| 2024 | DRAGON |
| 2025 | SNAKE |

> Tap `<` or `>` to navigate across years and see each year's zodiac.

---

## 📂 Folder Structure

```
LunarZodiacArray/
├── ContentView.swift
├── LunarZodiacArrayApp.swift
└── Assets.xcassets/
    ├── RAT.png
    ├── OX.png
    ├── ...
```

---

## 👩‍💻 Author

**Mansi K**  



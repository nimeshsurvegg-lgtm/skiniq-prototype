# SkinIQ ✨🧖‍♀️
**AI-guided skin scans and personalized routines built around your results.**

SkinIQ is a mobile-first web application prototype designed to simulate an intelligent, personalized skincare assistant. By combining a cosmetic questionnaire with mock AI-driven image analysis, the app estimates skin health metrics and generates tailored product recommendations.

## 🌟 Key Features

* **Authentication & User State**
    * Simulated user registration and login[cite: 2].
    * "Guest Mode" for frictionless testing without saving data[cite: 2].
    * LocalStorage integration to securely save user history and past scan reports across sessions[cite: 2].
* **Dual-Mode Analysis Engine**
    * **Photo Scan:** Uses the device's live camera (or file upload) to capture front, left, and right profile angles[cite: 2].
    * **Questionnaire-Only Mode:** Allows users to skip the camera scan and receive an estimated baseline score strictly from their lifestyle and skin history inputs[cite: 2].
* **Dynamic Questionnaire**
    * Adaptive questioning covering skin type, sun exposure, diet, sleep, and hydration levels[cite: 2].
* **Comprehensive Skin Health Report**
    * Overall Skin Health Score (out of 100)[cite: 2].
    * Detailed breakdowns of Sebum/Oil levels, Hydration, Pigmentation, and Texture[cite: 2].
    * Estimated spot counts (active acne, inflamed, comedones)[cite: 2].
* **Personalized Skincare Routines**
    * AI-curated product recommendations (e.g., Salicylic Acid vs. Ceramide Cream) based on the calculated skin profile[cite: 2].
    * Highlighted root causes and daily hygiene tips[cite: 2].
* **UI/UX Excellence**
    * Dark Mode and Light Mode toggling[cite: 2].
    * Smooth CSS animations, custom SVG icons, and responsive mobile-first layout[cite: 2].

## 🛠️ Tech Stack

SkinIQ is built as a highly portable, zero-dependency, single-file application[cite: 2].

* **Frontend Structure:** HTML5[cite: 2]
* **Styling:** Vanilla CSS (CSS Variables, Flexbox, Custom Keyframe Animations)[cite: 2]
* **Logic & State Management:** Vanilla JavaScript (ES6)[cite: 2]
* **Data Persistence:** Browser `localStorage`[cite: 2]
* **Typography:** Google Fonts (Inter, IBM Plex Mono)[cite: 2]

## 🚀 Getting Started

Since this is a client-side only prototype, there is no complex build process, server, or database required[cite: 2].

### Prerequisites
* A modern web browser (Chrome, Safari, Firefox, Edge).
* *Note: The live camera feature requires the file to be served over HTTPS or `localhost` to bypass browser security restrictions. Uploading images works locally.*

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/skiniq.git](https://github.com/yourusername/skiniq.git)

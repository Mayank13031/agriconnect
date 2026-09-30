# AgriConnect – Smart Farming Assistant 🌱

AgriConnect is a lightweight, responsive web application designed for farmers, agricultural students, and hobbyist growers. It provides intelligent crop recommendations, simulated plant health analysis, and farm care reminders.

---

## 🚀 Features

### 1. 🌾 Crop Guide & Suitability Calculator
- Recommends optimal crops based on **Location**, **Season** (Kharif, Rabi, Zaid), and **Soil Type** (Alluvial, Black, Red, Sandy).
- Displays key details:
  - Days to harvest
  - Watering frequency
  - Tailored cultivation tips
  - Compatibility rating (%)
- Real-time weather sample integration for selected regions.

### 2. 🍃 Plant Health Checker (Simulation)
- Upload leaf photographs to inspect for potential leaf diseases or nutrient deficiencies.
- Provides immediate diagnostic feedback with confidence scores and recommended next steps / mitigation actions.

### 3. 🗓️ Farm Care Reminders & Scheduler
- Automatically generates a complete sowing-to-harvest care schedule:
  - Sowing & initial watering
  - Periodic irrigation schedule
  - Weeding & pest inspection milestones
  - Fertilizer application reminders
  - Harvest readiness check
- Persists reminder checklist and task completion status using browser `localStorage`.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic markup for accessibility and responsive layouts.
- **Vanilla CSS**: Clean, modern responsive design with automatic Dark/Light mode support based on system preferences.
- **JavaScript (ES6+)**: Zero external dependencies, fast and lightweight DOM manipulation and state management.

---

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Mayank13031/agriconnect.git
   cd agriconnect
   ```
2. Open `index.html` in any modern web browser:
   - On Windows: double-click `index.html` or run `start index.html`
   - Or use VS Code Live Server extension.

---

## 🌐 Deploying to GitHub Pages

1. Navigate to your repository settings on GitHub: **Settings > Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the `main` branch and `/ (root)` folder, then click **Save**.
4. Your application will be live at `https://mayank13031.github.io/agriconnect/`!

# 🌱 Greeins — AI-Powered Tree Adoption & Growth Monitoring (Frontend + AI Models)

**Greeins** is a web-based platform designed to promote environmental sustainability by encouraging users to adopt trees and monitor their growth. The system uses integrated AI/ML models directly in the frontend to analyze plant health and development through image uploads.

Live Link - 

## 🎯 Objective

To provide an intuitive and intelligent tool for individuals to:
- Adopt trees digitally 🌳
- Monitor their plant’s growth 📈
- Detect potential diseases 🦠
- Receive care tips using AI 🤖
- Encourage responsible green behavior 🌍

---

## 🚀 Key Features

- 📸 **Image-Based Growth Analysis**:
  - Upload plant images across weeks (e.g., Week 1 vs Week 2)
  - AI estimates growth percentage based on:
    - Height
    - Leaf count
    - Leaf area and color quality

- 🧠 **Disease Detection**:
  - Integrated ML model identifies common plant diseases from uploaded images
  - Displays probable disease names and visual cues

- 💡 **Smart Care Tips**:
  - Watering schedules
  - Fertilizer suggestions
  - Sunlight needs — based on plant condition

- 📊 **Visualization**:
  - Simple graphs showing growth trends
  - Visual indicators of health/disease over time

- 🌐 **Fully Frontend-Based**:
  - Built using HTML, CSS, and JavaScript
  - ML models run in-browser (using TensorFlow.js or integrated Python-in-the-browser tools)

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **AI Models**:
  - Custom trained models for:
    - Leaf detection & counting
    - Disease classification
    - Growth estimation
  - Model formats: TensorFlow.js or ONNX (for browser compatibility)
- **Visualization**: Chart.js / D3.js / Custom SVG-based components
- **Optional IoT Simulation**: JSON-based dummy sensor values for temperature, moisture, etc.

---

## 📈 Sample IoT Data (for demo)

```json
{
  "temperature": 28.4,
  "humidity": 65,
  "soil_moisture": 58,
  "light_intensity": 720,
  "timestamp": "2025-07-19T10:00:00"
}

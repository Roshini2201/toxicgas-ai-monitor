# 🏭 ToxicGas AI Monitor

ToxicGas AI Monitor is a real-time, AI-powered industrial pollution monitoring dashboard built with Streamlit. It provides comprehensive monitoring of factory emissions (CO₂, NO₂, and SO₂), assesses health risks, generates automated reports, and offers AI-driven suggestions for pollution reduction.

## 🌟 Key Features

- **📊 Real-time Dashboard**: Live monitoring of CO₂, NO₂, and SO₂ levels with interactive Plotly charts.
- **🧠 AI Health Estimator**: AI-powered health risk assessment based on current and historical pollution data.
- **💡 AI Suggestions**: Intelligent, priority-based recommendations for pollution reduction and mitigation.
- **🚨 Intelligent Alert System**: Automated alerts for dangerous pollution levels and compliance violations.
- **📧 Automated Reports**: Generates and simulates sending daily environmental audit reports.
- **🛰️ Satellite Comparison**: Compares factory emission data against regional averages using simulated satellite data.
- **🔄 Offline Sync**: Local database caching to ensure data isn't lost during network outages, with manual and automatic sync options.

## 📁 Project Structure

- `app.py`: The main Streamlit application and UI layout.
- `data_simulator.py`: Simulates real-time industrial pollution data.
- `ai_estimator.py`: Calculates health risks, audits scores, and generates alerts.
- `report_generator.py`: Generates Markdown-based compliance/shutdown reports and handles email simulations.
- `ui_components.py`: Contains custom Plotly charts and Streamlit UI components.
- `offline_sync.py`: Manages SQLite database operations for offline capabilities.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed on your system.

### Installation

1. Clone this repository or navigate to the project directory:
   ```bash
   cd toxicgas-ai-monitor
   ```

2. Install the required dependencies:
   ```bash
   pip install streamlit pandas numpy plotly
   ```

### Running the Application

Start the Streamlit application by running the following command in your terminal:

```bash
streamlit run app.py
```

The application will automatically open in your default web browser at `http://localhost:8501`.

## ⚙️ Configuration

Use the sidebar in the application to configure:
- **Factory Type**: Switch between different factory profiles (Coal Power Plant, Textile Factory, Chemical Plant, etc.) to see tailored AI suggestions.
- **Monitoring Status**: Start or stop the live data stream.
- **Offline Sync**: Force sync local data if the system goes offline.

## 📜 License

This project is created for demonstration and monitoring purposes.

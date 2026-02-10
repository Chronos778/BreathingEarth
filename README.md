# Breathing Earth 🌍

An interactive climate intervention dashboard that simulates the effects of greenhouse gas emissions and demonstrates the potential impact of climate intervention technologies.

## Overview

Breathing Earth is a web-based simulation that visualizes the progression of climate degradation from 2029 to 2047. Users can observe real-time changes in global temperature anomaly and greenhouse gas concentrations, then deploy intervention solutions to witness ecosystem recovery.

## Features

- **Real-time Climate Simulation**: Watch as global temperature and greenhouse gas levels increase over time
- **Interactive Visualization**: Dynamic video backgrounds that reflect climate conditions
- **Greenhouse Gas Monitoring**: Track four key greenhouse gas categories:
  - Sulphur Hexafluoride (SF₆) & HFCs
  - CFC-12 & Fossil Methane (CH₄)
  - Nitrous Oxide & CFC-12
  - HFC-23 & Carbon Dioxide (CO₂)
- **Intervention Deployment**: Deploy plasma reactors and Direct Air Capture (DAC) systems
- **Recovery Animation**: Watch as intervention technologies reverse climate damage
- **Pause/Resume Controls**: Control the simulation timeline
- **Reset Functionality**: Restart the simulation to explore different scenarios

## How It Works

### Degradation Phase
The simulation begins in 2029 with a global temperature anomaly of +2.13°C. Over 18 years:
- Temperature rises to +3.82°C by 2047
- Greenhouse gas concentrations increase steadily
- Visual and textual warnings escalate as conditions worsen
- Background video reflects deteriorating conditions

### Intervention Phase
When you deploy the solution:
1. **Plasma Reactors** activate to decompose SF₆ and HFCs
2. **DAC Units** come online to extract atmospheric CO₂
3. **Methane Capture Systems** engage to reduce CH₄ levels
4. Temperature begins to decrease
5. Greenhouse gas levels drop significantly
6. Background video transitions to show recovery

### Recovery Phase
After intervention:
- Global temperature drops to +1.62°C
- All greenhouse gas levels stabilize or decrease
- Ecosystem recovery begins
- Visual indicators turn green to show improvement

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No additional dependencies required

### Installation

1. Clone this repository:
```bash
git clone https://github.com/SC136/BreathingEarth.git
```

2. Navigate to the project directory:
```bash
cd BreathingEarth
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Alternatively, you can serve the files using a local web server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Usage

1. **Observe**: Watch the simulation run automatically from year 2029
2. **Monitor**: Track temperature changes and greenhouse gas levels
3. **Pause**: Use the pause button to freeze the simulation
4. **Deploy**: Click "Deploy Solution" to activate intervention technologies
5. **Reset**: After recovery, click "Reset Simulation" to run the scenario again

## Technologies Used

- **HTML5**: Structure and video playback
- **CSS3**: Styling, gradients, and animations
- **JavaScript (Vanilla)**: Simulation logic and interactivity
- **Video**: MP4 format for visual storytelling

## Project Structure

```
BreathingEarth/
├── index.html          # Main application file
├── bad.mp4            # Video showing climate degradation
├── good.mp4           # Video showing ecosystem recovery
└── README.md          # This file
```

## Educational Purpose

This simulation is designed to:
- Raise awareness about climate change impacts
- Demonstrate the potential of intervention technologies
- Illustrate the relationship between greenhouse gases and global temperature
- Show that climate action can make a measurable difference

## Technical Details

### Simulation Parameters
- **Timeline**: 2029-2047 (18 years)
- **Temperature Range**: +2.13°C to +3.82°C (degradation), down to +1.62°C (recovery)
- **Update Interval**: 1.5 seconds per year
- **Gas Tracking**: 4 major greenhouse gas categories

### Intervention Technologies
- **Plasma Reactors**: Decompose SF₆ and HFCs through high-temperature plasma
- **Direct Air Capture (DAC)**: Extract CO₂ directly from the atmosphere
- **Methane Capture**: Reduce atmospheric CH₄ concentrations

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Improve the simulation model
- Enhance the visual design
- Add educational content

## License

This project is available for educational and non-commercial use.

## Acknowledgments

Created to demonstrate the potential impact of climate intervention technologies and inspire action on climate change.

---

**Note**: This is a simplified educational simulation. Actual climate systems are far more complex, and real-world climate intervention requires careful consideration of scientific, ethical, and environmental factors.

# Moment of Inertia of Flywheel - Physics Lab Report

## Overview
This is an interactive web-based physics lab report for **Experiment No. 4: Determination of the Moment of Inertia of a Flywheel**. 

The application uses the principle of **conservation of energy** to calculate the moment of inertia and generates professional graphs for experimental data visualization.

## Features
- **Interactive Calculation Table**: Input experimental data for multiple observations
- **Automatic Calculations**: Computes angular velocity (ω) and moment of inertia (I)
- **Dynamic Graphs**: 
  - Angular Velocity vs Observation Number
  - Moment of Inertia vs Observation Number
- **Downloadable Outputs**:
  - Export graphs as PNG images
  - Download complete report as PDF
- **MathJax Support**: Professional mathematical notation for formulas

## Formulas Used

### Angular Velocity
$$\omega = \frac{4\pi N}{t}$$

### Moment of Inertia
$$I = \frac{NM}{N+n} \left( \frac{2gh}{\omega^2} - r^2 \right)$$

where:
- **M** = Mass (kg)
- **h** = Height (m)
- **r** = Radius (m)
- **n** = Gear ratio parameter
- **N** = Number of rotations
- **t** = Time (s)
- **g** = Gravitational acceleration (9.81 m/s²)

## How to Use

1. **Enter Experimental Data**: Fill in the input fields for each observation:
   - Mass M (kg)
   - Height h (m)
   - Radius r (m)
   - Parameter n
   - Number of rotations N
   - Time t (s)

2. **Calculate**: Click the **Calculate** button to:
   - Compute angular velocity and moment of inertia
   - Update result table with values
   - Generate/update experimental graphs

3. **Download Results**:
   - **Download Graphs**: Export individual graphs as PNG files
   - **Download PDF**: Generate complete lab report as PDF

## Graph Details

### Graph 1: Angular Velocity vs Observation Number
- **Title**: Angular Velocity vs Observation Number
- **X-axis**: Observation Number
- **Y-axis**: Angular Velocity, ω (rad/s)

### Graph 2: Moment of Inertia vs Observation Number
- **Title**: Moment of Inertia vs Observation Number
- **X-axis**: Observation Number
- **Y-axis**: Moment of Inertia, I (kg·m²)

## Technologies Used
- **HTML5**: Document structure
- **CSS3**: Professional styling and responsive design
- **JavaScript**: Calculations and interactivity
- **Chart.js**: Graph visualization
- **MathJax**: Mathematical formula rendering
- **html2pdf**: PDF export functionality

## GitHub Pages Setup

### To Host on GitHub Pages:

1. **Go to your repository settings**:
   - Navigate to `Settings` → `Pages`

2. **Configure GitHub Pages**:
   - Source: Select `Deploy from a branch`
   - Branch: Select `main`
   - Folder: Select `/ (root)`
   - Click **Save**

3. **Access your lab report**:
   - Your site will be available at: `https://mdimtiazahmednahid.github.io/labs.nahid/`
   - Direct link to lab report: `https://mdimtiazahmednahid.github.io/labs.nahid/index.html`

## File Structure
```
labs.nahid/
├── README.md              # This file
├── index.html             # Main lab report application
└── .git/                  # Git repository
```

## Installation & Development

No installation required! Simply open `index.html` in a web browser to use locally.

### Local Testing:
```bash
# Clone the repository
git clone https://github.com/mdimtiazahmednahid/labs.nahid.git
cd labs.nahid

# Open in browser (use a local server for best results)
python3 -m http.server 8000
# Then navigate to http://localhost:8000
```

## Notes
- All calculations are performed client-side (no server required)
- Data is not saved between sessions (refresh will clear inputs)
- Graphs update dynamically as calculations are performed
- PDF export works best in modern browsers (Chrome, Firefox, Edge, Safari)

## Author
NAHID@HEXAGONLAB

## Copyright
© All rights reserved. Visit [www.hexagonlab.org](https://www.hexagonlab.org)

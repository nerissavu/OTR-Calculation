# 💧 Wastewater Treatment DO Simulator

A [Streamlit](https://streamlit.io)-based application for simulating dissolved oxygen (DO) profiles in wastewater treatment aeration tanks.

## 🎯 Key Features

* Real-time DO profile simulation
* Interactive parameter adjustment
* Visualization of oxygen transfer dynamics
* DO threshold monitoring
* Time-series analysis of oxygen levels
* Customizable operating parameters

## 🧮 Calculations

The simulator performs the following calculations:
* Oxygen Transfer Rate (OTR)
* DO concentration over time
* Net oxygen balance considering:
  * Transfer efficiency
  * Consumption rate
  * Saturation effects

## 📊 Input Parameters

* Operational Parameters:
  * Oxygen Transfer Efficiency (OTE, %)
  * Oxygen Consumption Rate (mg/L/min)
  * Initial DO Level (mg/L)

## 💻 How to Use

1. Adjust the parameters in the sidebar:
   * Set Oxygen Transfer Efficiency
   * Define Consumption Rate
   * Set Initial DO Level

2. The simulator will automatically:
   * Calculate DO profile
   * Update visualization
   * Show threshold compliance
   * Display final DO level

## 📈 Output

The simulator provides:
* Real-time DO concentration plot
* Minimum DO threshold indicator
* Final DO level display
* Time-series visualization
* Parameter sensitivity analysis

## 🔬 Theory

The simulation is based on:
* Mass transfer principles
* Oxygen saturation dynamics
* Microbial consumption kinetics
* Two-film theory of gas transfer

### Key Equations:
* DO Change = OTR × (1 - DO/DOsat) - Consumption Rate
* Where:
  * OTR = Oxygen Transfer Rate
  * DOsat = Saturation DO (typically 9.0 mg/L)
  * Consumption Rate = Microbial oxygen uptake
